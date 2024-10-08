Given an unorganized pile of books, do the following:

1. LET alpha_set be an empty list of books in alphabetical order.
2. Take a book from pile.
3. PUT the same book into alpha_set.
4. Take another book (taken_book) from pile.
5. IF the taken_book is alphabetically before any book in alpha_set, then put the taken_book before that book.
6. IF the taken_book is alphabetically after any book in alpha_set, then put the taken_book after that book.
7. OTHERWISE, the taken_book is alphabetically equivalent to a book in alpha_set. Put the taken_book after that book.
8. If pile p is not empty, go to step 4.