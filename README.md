Create an application that will provide an opportunity to read e-books. You should use the techniques and practices that were demonstrated in our lecture.

Requirements:
1. Provide the opportunity to download a text file from the server (new Book ('http://google.com/text..txt', ...)) or by entering text (new Book ('Text ...', ...); )  
  1.1 You need to provide possibility to get access to object after you creating new instance (use global scope)
2. 1 page == 200 characters
3. Implement methods that provided below

```book.startReading ()``` => start reading -> should return first book page  
```book.nextPage ()``` => should move to the next page  
```book.prevPage ()``` => should move to the previous page  
```book.jumpTo ()``` => should jump to a specific page  
```book.find ()``` => should provide some text in the book and return a specific page where text was found (can be several pages)  
```book.continue ()``` => should return to the page where you end your reading, and continue reading process  
```book.author ()``` => should return book author  
```book.price ()``` => should return book price  
