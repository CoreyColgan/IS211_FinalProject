# IS211_FinalProject
Final Project for IS211

Project Option 1: Book Catalogue Details:The purpose of this web application is to provide the end user with a fuctional 
interface that will allowthe user to keep track of the books they own. The primary screen, after logging in, will show the 
user the books they have saved so far. Initially, this list will be blank. Users are also presented a form tosearch for books 
by ISBN. Once filled out, the application will use the Google Book API to search forthe book via ISBN.To do this, let us take a 
look at an example. To search for a given ISBN, like 9781449372620 , you cannavigate to 
https://www.googleapis.com/books/v1/volumes?q=isbn:9781449372620 and receive a JSON response that includes all sorts of metadata on the book. For now, we only need to show andstore for the user the title, the author, page count and average rating. If there is any error in processingthe JSON, you should return an appropriate error to the user. Sometimes, the API will come back withmultiple results. For now, you can use the first result that comes back.The application should also allow the deletion of books. This will allow the user to delete a book fromtheir list (either because they made a mistake, or they sold the book, etc).
