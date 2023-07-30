# Book-API Project 📕

The Book-API project is a simple Spring Boot RESTful API that allows users to manage a collection of books. Users can perform various CRUD (Create, Read, Update, Delete) operations on books using this API. The API stores book information such as book name and author name in a database.
<br>

## Features ✨

- **Get a Single Book:** Retrieve information about a specific book by its ID.
- **Get All Books:** Retrieve a list of all books available in the database.
- **Add a Book:** Add a new book to the database.
- **Update a Book:** Update the details of an existing book.
- **Delete a Book:** Remove a book from the database by its ID.
<br>

## Technologies Used 🌐

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- RESTful API
- JSON
- MySQL
- PostMan (For testing APIs)
<br>

## Project Structure 📂

The project consists of several components, each serving a specific purpose:

1. **BookController:** Defines the RESTful endpoints for handling book-related requests. It interacts with the BookService to perform various operations.

2. **BookService:** Contains the business logic for book-related operations. It interacts with the BookRepository to access the database.

3. **BookRepository:** Provides access to the database using Spring Data JPA. It extends the JpaRepository interface to enable CRUD operations.

4. **BookEntity:** Represents the entity (model) for a book. It is annotated with `@Entity` to indicate it's a JPA entity and corresponds to a database table.
<br>

## How to Run the Project 💨

1. Ensure you have Java and MySQL installed on your system.
2. Clone or download the project from the repository.
3. Import the project into your preferred IDE (e.g., Eclipse, IntelliJ).
4. Set up the MySQL database and update the database configurations in the `application.properties` file (not provided in the code).
5. Build and run the project using the IDE or by running `mvn spring-boot:run` command from the project root directory.
<br>

## API Endpoints 👨🏻‍💻

1. **GET /book:** Returns information about a single book (hardcoded book data).
2. **GET /getbooks:** Returns a list of all books available in the database.
3. **GET /book/{id}:** Returns information about a specific book with the given ID.
4. **POST /postbook:** Adds a new book to the database.
5. **DELETE /deletebook/{id}:** Deletes a book from the database with the given ID.
6. **PUT /updatebook/{bookid}:** Updates the details of a book with the given ID.
<br>

## ‼️ Important Note ‼️

- The code provided is not fully complete and might not work as expected without certain dependencies and configurations.
- You need to set up the database and make sure the application properties are correctly configured to run the project successfully.
<br>

## Upcoming Update
Adding more features, error handling, authentication, and security measures.
<br>
<br>

## Contributing 🤗

Feel free to explore and use these project. If you encounter any issues or have suggestions for improvements, please feel free to contribute or reach out for assistance.

Contributions are always welcome! ✨

See [`contributing.md`](https://github.com/ajaynegi45/Book-API/blob/main/contributing.md) for ways to get started.

Please adhere to this project's [`code_of_conduct.md`](https://github.com/ajaynegi45/Book-API/blob/main/code_of_conduct.md).
<br>

## Contact Information 📧

If you have any questions or would like to connect, please don't hesitate to reach out. I'd be more than happy to chat and learn from your experiences too.
<br>
<br>
**Email:** contact@ajaynegi.co
<br>

## Thankyou ❤️
Thank you for taking the time to explore my project. I hope you find them informative and useful in your journey to learn Java and enhance your programming skills. Your support and contributions are highly appreciated. 
Happy coding! ✨
<br>

## Authors

- 🙍🏻‍♂️ [@ajaynegi45](https://github.com/ajaynegi45)
