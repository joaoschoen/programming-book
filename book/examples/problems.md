# Problems

[Return to book](../content.md#chapter-4-problems-problem-solving-functions-wip)

I want to show with this example that computing is way more normal then you'd think, and that we can look at real world problems with the lens of the logic of computers and programmers.

## A book

Going back to my [abstraction](abstraction.md) example, let's think again about what a book is. 

A book is made of pages, which are pieces of paper with a number and a collection of words that we call the text of the book. 

For the sake of these examples we have no information about the book other then this, so we don't know how many pages the book has, and we don't know that the book's pages are ordered.

### Finding a page in a book

Say I give you a book, and I tell you to open the book on page 302, you don't know exactly where this page is from the start so you have to search for it, and let's also say that you don't know how many pages the book has. 

The naive approach to solve this problem is opening the book on page 1, then flipping through the pages one by one until you get to page 302.

To do this you open a page, look at the number, you then ask your self if this is the page you want to get to, if it isn't you continue, if it is then you stop and you now have your answer.

This way tries to brute forcing the problem by going through each page to find the one we wanted to look at, but there's a few problems that comes out of that.

## The problems with brute forcing

### Lack of information 

Let's say that we are told to go to page 500, since we don't know how many pages the book has, if the book has 499 pages, by using this method we'll look through all of the book's pages and at the end we won't find the page we are looking for because it doesn't exist.

We can be smarter about this because we know that books are always ordered, so the numbers of the pages will always be in order. 

By having this information, before trying to solve the problem we were given we can first open the last page of the book and take note of the page number, now we know how many pages there are.

So we can solve the problem of trying to look for a page that we know doesn't exist.

### Optimization

Another thing we can while still doing this brute force approach is trying to reduce the number of pages we have to look through to solve this problem faster.

Since we know now the number of pages that the book has, we can look at the page we have to go to, we can ask ourself if this page is closer to the start of the book or the end of the book.

So instead of going always from the start and going to the end, we can start at the end and go to the start. 

If before we had a book with 500 pages and we wanted to go to page 400 we can start at the end of the book, if we want to go to page 100 we can start at the start of the book.

By doing this the maximum number of pages we have to go through is half the number of pages in the book.

### Solving brute force with binary search

When we look at a page we compare the page we want to go to with the page we are currently at.

Is 300 equal to 250? no, this is false. 

Is 300 equal to 300? yes, this is true.

This is how we decide if we stop looking or not, these comparisons by nature are binary, meaning they can only have these two possible answers, true or false.

Since we know that the book is always ordered what we can do is we instead of opening the book at the first page, opening it at the middle. 

We are looking again for page 302, and we know that our book has 1000 pages. By opening it in the middle we are at page 500, we then ask ourself if the page we want to go comes before page 500 or after page 500.

We know that page 302 comes before page 500, and since we know it is before, we can ignore then the later half of the book, by answering this binary question we have reduced the number of pages we have from 1000 to 500.

We then do the same thing again, we look at the first 500 pages of the book as it's own collection of pages, we look at the page in the middle and we're now on page 250.

We know that page 302 comes after page 250, so we then can ignore the first 250 pages, bringing down the number of pages we have to look at from 500 to 250, each time we do this we reduce the number of pages by half.

If you keep doing this you'll eventually reach the page you have to go to way faster then before, and if you think about the way you try to find a page in a book this is usually the way you do it.

## Counting names

Now let's think of a different problem, let's say I give you a book and a list of character names, and I ask you to count the number of times that each name appears in the book.

We can't solve this problem all at once, we have to break it down into smaller pieces to be able even think about it properly.

We write the names down on a piece of paper, we open the book on page one.

We then have to read each word of that page and compare it to our list. Each time we find one of our names we increase the number of times we have found that name by one. 

We then repeat this process for each page of the book, and by the end we will know how many times each name appears.

Notice that this problem can not be optimized like the last one, because we can't ignore any word, because any of the words could be one of the names we are looking for.

## Playing cards

Now let's think about a deck of playing cards, it is a collection of cards, each cart has two pieces of information about it, the value of the card and the suit of the card.

The value of a card can be one of the following:

[Ace,2,3,4,5,6,7,8,9,10,Jack,Queen,King]

And the suit of the card can be one of the following:

[Spades, Clubs, Hearts, Diamonds]

## Ordered and unordered collections

When the open a new pack of playing cards they are usually ordered, the come ordered by suit and by value, so the first card could be the Ace of Hearts, the second would be the 2 of Hearts, and so on...

### Transforming an ordered collection into an unordered collection

If we shuffle this deck of cards, we change the original order that the deck came in, and it then goes from being an ordered collection of cards to being an unordered collection of cards.

If we then try to search for a card and we compare to searching for a page in a book we can't make any of the assumptions that we could before, because we don't have enough information to make those assumptions.

In the case of the book, the content of the book, the information in the text, to the problems we were trying to solve was interchangeable, we treated any bit of text to have the same value as any other bit of text, so our pages were interchangeable.

In the case of the deck of cards we care about the information in the card, when we are looking for a specific card we now care for value and the suit of the card, so each card is unique. 

### Searching for a card in a shuffled deck

Since in a shuffled deck of cards the order of the cards is random, we can't make any comparisons and assumptions, we have to necessarily look through all of the cards to find the card we are looking for.

So the worst case scenario here is that our card is at the end of the deck, so we have to look through all of the deck.

## Collections and sets

We have defined that both the book and the deck of cards are collections of objects, and that there is a rule that defines what is part of the collection and what isn't.

In the case of the book, every object in the world that we can classify as a page, can be part of the collection of pages that we call a book.

The same can be said about the deck of cards, each object that has the properties of a card can be a part of the collection of cards that is a deck of cards.

In mathematics these collection of objects with defined rules of what is part of the collection and what isn't is called a set.

### Defining what is the order in a set

The process of ordering an unordered set is called sorting, but to consider our set to be sorted we have to define a rule that says tells us how we should compare two objects of the same set and tell if one comes before or after the other. 

In the case of the pages of a book we define that the number of the page is what tells us the order, if a page number is bigger then the other it goes after, if not it goes before.

In the case of the deck of cards there isn't a definite rule, we can chose multiple ways of defining what is this rule. 

Because cards have both values and suits we could define that a sorted deck of cards is one in which the cards are in order of the value of the cards, ignoring the suit of the card.

### Transforming an unordered collection into an ordered collection

The simplest way of doing this creating a second deck of cards, we then remove a card from the first deck and put it in the second deck, since there were no cards in the second deck and we put one in it, the second deck is now sorted.

We then take another card and do the same, we look at the card that we have in our second deck and ask if it comes before or after that card, if it goes before we put it before if it goes after we put it after.

Then we do the same for each of the other cards of the first deck, each time we go through all of the cards in the second deck and use the rule of sorting we defined to see where the card goes and we put that card there.

After all cards are moved from the first to the second deck, the second deck will be sorted.

[Return to book](../content.md#chapter-4-problems-problem-solving-functions-wip)
