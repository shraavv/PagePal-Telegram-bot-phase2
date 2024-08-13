# Gopal and his PagePal

Meet Gopal, a book enthusiast who has a great passion for reading books. He ran into trouble trying to locate his favourite books, which led to him coming up with an idea of creating a chatbot which would assist him by recommending a list of books with the necessary details. Unfortunately, Gopal's lack of programming skills proved a significant obstacle in making his "PagePal" a reality.

As a programmer, help Gopal in uniting him with his PagePal!

Create a book recommendation telegram bot that displays a list of books with details like Book title, author, description, year published (originally), language and preview (if available) when the user types in the genre of the book they want to read.

Feel free to customise your PagePal with more features ;)


# Primary Features

- Before you start coding, set up your **python virtual environment**. This is an important step and always remember, Google is your friend :)
- The bot should have four basic commands:
  - ```/start``` returns a welcome message to the user
  - ```/book``` asks the user to type in the genre
  - ```/preview``` asks the user for the book name for which they need a preview link
  - ```/list``` asks the user to type in a specific book name and then it returns a message to execute ```/reading_list``` command
  - ```/reading_list``` displays three buttons
    - **Add a book**: Press this button to add a new book to the reading list
    - **Delete a book**: Press this button to remove a book from the reading list
    - **View Reading List**: Press this button to return the reading list (docx)
  - ```/help``` returns the list of commands with their description
- When the ```/book``` command is typed in, the user is asked to enter the genre name, upon which the bot returns a CSV file with different book names and their details. The CSV file should have different columns for each detail.
- When the ```/preview``` command is typed in, the user is asked to enter the book name, upon which it redirects us to the preview link.
- Reading list should be **docx** format and should contain the book title and preview link (if available), bonus points if you could customize the way results are displayed in the doc :)
- Note that the reading list should remain unchanged unless ```Add a book``` or ```Delete a book``` button is pressed

Also ensure that you complete this task using **python.**

# Resources

- [Google Books API](https://developers.google.com/books/docs/v1/using)
