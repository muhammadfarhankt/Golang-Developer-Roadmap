# Golang Developer Roadmap

### Welcome. Hey everyone! I'm a fellow Golang enthusiast, still on the path to becoming a pro backend developer. This repository is my way of sharing what I've learned so far and creating a space for others like me to learn and grow together. Whether you're just starting out or looking to brush up on your skills, feel free to join the journey!


#### Understanding web fundamentals like HTML, CSS, and basic JavaScript can be beneficial for backend developers. This knowledge helps bridge the gap between front-end and back-end functionalities, especially when debugging or troubleshooting issues.

1. **HTML & CSS** https://github.com/muhammadfarhankt/MERN-Stack-Developer-Roadmap/tree/main?tab=readme-ov-file#-1-html-click-for-expanding/
2. **Bootstrap, Basic Javascript, DOM Manipulation** https://github.com/muhammadfarhankt/MERN-Stack-Developer-Roadmap/tree/main?tab=readme-ov-file#-2-bootstrap-basic-javascript-dom-manipulation-/

#### Research & Learn following topics in detail. Watch videos & Read documentations / tutorial sites.

<details>
  <summary><h2>1. Learn the Golang fundamentals(Click for expanding)</h2> </summary>

- Go Tour: Start with the official Go Tour to get familiar with the language syntax and features. [Visit A Tour of Go to begin.](https://go.dev/tour/welcome/1/)
- W3Schools: Utilize W3Schools' Go tutorial for a structured introduction to the language. Visit W3Schools Go Tutorial to get started.[https://www.youtube.com/watch?v=un6ZyFkqFKo&ab_channel=freeCodeCamp.org]
- Your Master Plan to Learn Golang Fast and Deep (2024 Edition) : https://medium.com/p-society/master-plan-to-learn-golang-edbf85c7ae83
- Video Tutorials: If you prefer video learning, check out this tutorial from Freecodecamp: Go Programming – Golang Course with Bonus Projects.[https://www.youtube.com/watch?v=un6ZyFkqFKo&ab_channel=freeCodeCamp.org] (Watch the first few chapters up to slices).
- Learn by doing. Install golang on your system or start by doing Golang Online compilers.[https://www.programiz.com/golang/online-compiler/]
- GeeksforGeeks: Dive deeper into Golang fundamentals on [Geeksforgeeks](https://www.geeksforgeeks.org/golang/) for comprehensive learning.
- Short Variable Declaration: Utilize the short declaration syntax (:=) to declare variables without assigning garbage values. Defaults to zero (0) or false for boolean.
- [Golang if else Statements](https://www.scalent.io/golang/golang-if-else-statement/)
- Loop Types: Master different loop types including range loops and understand loop approaches (while, do while, infinite loop).
- Arrays vs Slices: Differentiate between arrays and slices, focusing on capacity management and slice behavior on overflow. Understand that slices are built on top of arrays and provide a more flexible way to work with data collections. When a slice's capacity is exceeded, Go automatically doubles the underlying array's size to accommodate additional elements. This dynamic resizing ensures efficient memory usage and allows slices to grow dynamically as needed.
- Strings in Go: Learn about the string data type, byte vs rune, immutability, and string manipulation techniques.
- Functions: Explore the flexibility of functions in Go, including returning multiple data types and variadic functions.
- Initialising a project. `go mod init <project name>`
- Maps and Structs: Explore Go's map and struct data types, including declaration, manipulation, size, and capacity.

## 1.1 Now it's time to learn Golang special features

- Understanding Go: Explore the reasons behind Go's creation and its design philosophy.
- _(underscore) indentifier.
- Packages and Modules: Understand Go's package system, including importing/exporting packages. Practice writing functions in other packages and importing them. Remember to capitalize function names for exporting.
- [Multi-Platform Builds with go build](https://www.scalent.io/golang/go-build/)
- [Golang Type Casting or Conversion – Detailed Guide](https://www.scalent.io/golang/golang-type-casting/)
- Error Handling: Treat errors as a data type and learn effective error handling techniques.
- Understand following new vs make, GO Path and GO Root
- Goroutines and Channels: Learn about Go's powerful concurrency features, including goroutines and channels.
- [For loop in Golang - A complete guide](https://www.scalent.io/golang/for-loop-in-golang/)
- OOP Concepts in Go: Understand how Go implements object-oriented programming (OOP) concepts and whether it follows OOP or procedural programming (POP) paradigms.
- Defer: Understand the defer statement and its role in handling function execution flow.
- Concurrency vs Parallelism: Differentiate between concurrency and parallelism in the context of Go programming.

</details>

<details>
  <summary><h2>2. Learn Web Fundamentals with Golang</h2> </summary>
  
### URL Structure: Break down the components of a URL (Uniform Resource Locator):
- Scheme: The protocol (e.g., http:, https:).
- Host: The domain name or IP address of the server.
- Path: The specific resource being requested.
- Query String: Optional parameters appended to the URL after a question mark (?).
- Fragment: Optional anchor part within a document (e.g., for scrolling to a specific section).
### HTTP Fundamentals: Grasp the foundation of web communication:
- HTTP Protocol: Understand the Hypertext Transfer Protocol, the core protocol for communication between web clients (browsers) and servers. Learn about request methods (GET, POST, PUT, DELETE), request and response headers, and status codes.
- Stateless vs. Stateful Communication: Differentiate between stateless HTTP requests (independent) and stateful communication (where the server needs to maintain information about a user session across requests).
### Session Management: Explore techniques for maintaining state in web applications:
- Sessions: Understand how sessions enable applications to store user-specific data (e.g., login status, preferences) between requests. Learn about different session storage mechanisms like cookies, server-side storage (in-memory or database), or session management frameworks.
- Cookies: Familiarize yourself with cookies, which are small pieces of data sent by a server and stored on the client-side (user's browser) that can be used to maintain some state information between requests.
### HTTP Methods: Deepen your understanding of common HTTP request methods:
- GET: Used to retrieve data from a server (e.g., fetching a web page).
- POST: Used to submit data to a server (e.g., sending a form submission).
- PUT: Used to update existing data on a server.
- DELETE: Used to delete data from a server.
- Additional Methods: Explore other HTTP methods like PATCH (partial updates), HEAD (retrieve header information only), and OPTIONS (discover server capabilities).
### HTTP Versions: Understand the different versions of the HTTP protocol and their key features:
- HTTP/1.1: The most widely used version, supporting persistent connections (keeping connections open for multiple requests).
- HTTP/2: A more efficient version with features like multiplexing (sending and receiving multiple requests/responses concurrently over a single connection) and header compression.
### Web Frameworks: Explore popular Go web frameworks that simplify web development:
- Echo: A high-performance, minimalistic web framework.
- Gin: A flexible and efficient web framework known for its clean routing syntax.
- Gorilla: A modular toolkit for building web applications and APIs.
- Fiber: A high-performance, minimalist web framework with a focus on speed.
- Many Others: Research additional frameworks like Goji, Martini, and Negroni to find the one that best suits your project's needs. Consider factors like performance, ease of use, feature set, and community support.

## 2.1 Practice Project: Login System with Session Management

### Develop a Server-Side Login Page:

#### View Engines:
- With view engines, developers can create dynamic web pages by injecting data from the server-side application logic into predefined HTML templates. This separation of concerns between data and presentation enhances code maintainability and scalability in web projects.
- Explore view engines and their role in generating dynamic HTML content for web pages.
- Understand how view engines like HTML templates or server-side rendering frameworks work.
- Go's standard library provides the html/template package, which offers a robust template engine for generating HTML content.
- Server-side rendering frameworks like Gin, Echo, or Fiber often integrate seamlessly with view engines, allowing developers to define routes and render templates in a unified manner.
- View engines in Go typically follow the Model-View-Controller (MVC) pattern, where templates serve as the "view" layer responsible for presenting data to users.
- Enhances code maintainability by separating data and presentation concerns.

#####  We or in general Go community, frameworks are typically avoided due to the language's emphasis on simplicity, performance, and flexibility. Instead, we design architectures tailored to each project's needs, importing only necessary packages to ensure simplicity and optimal performance.
  
#### User Authentication:
- Implement server-side validation for username and password inputs.
- Verify user credentials against predefined values stored on the server.

#### Session Handling:

- Implement session management to maintain user authentication state.
- Ensure that sessions persist across requests and expire after a certain period of inactivity.

#### Login Page Functionality:

- Develop a login page that accepts username and password inputs from users.
- Display appropriate messages for incorrect username or password entries.

#### Home Page Access:

- Grant access to the home page upon successful authentication.
- Implement a signout button on the home page to log users out and redirect them to the login page.

#### Prevent Back Button Access:

- Implement measures to prevent users from accessing the home page using the browser's back button after signing out.

### Learn to create web-server using “net/http” package
### Create web-servers using Gin(so far the best router), learn middleware well.
  
</details>

<details>
<summary><h2>3. Learn SQL with PostgreSQL</h2></summary>

#### Understanding SQL vs. NoSQL
- **Relational (SQL) Databases**: Store data in tables with rows and columns.
  - Examples: PostgreSQL, MySQL.
- **Non-Relational (NoSQL) Databases**: Store data in various formats like JSON, key-value pairs, graphs, or documents.
  - Examples: MongoDB, Redis.
- **Web-scaled**: Learn how databases handle large amounts of data across many servers.
- **When to Use SQL vs. NoSQL**: SQL for structured data and complex queries, NoSQL for flexible, large-scale data storage.

#### SQL Data Types
- **null**: Represents missing or undefined data.
- **bit**: Stores binary values (0 or 1).
- **int**: Stores integer numbers.
- **real / float**: Stores floating-point numbers.
- **char, varchar, text**: Store text data.
  - `char` is fixed-length.
  - `varchar` is variable-length.
  - `text` is for long texts.
- **boolean**: Stores true/false values.
- **date, datetime, timestamp**: Store date and time information.
- **xml/json**: Store XML or JSON data.

#### SQL Operators
- **Arithmetic**: +, -, *, / (addition, subtraction, multiplication, division).
- **Logical**: AND, OR, NOT (used in conditions).
- **Comparison**: =, <>, >, <, >=, <= (comparing values).
- **Bitwise**: &, |, ^ (operations on binary representations).

#### PostgreSQL-Specific Data Types
- **interval**: Time intervals.
- **point**: Geometric points.
- **bigserial**: Auto-incrementing large integers.
- **Custom Types**: Create your own data types.

#### Database Fundamentals
- **Client/Server Model**: The database server manages data, clients connect to perform operations.
- **Database Cluster**: A collection of databases managed by a single server instance.
- **Constraints**: Rules to ensure data integrity.
  - **UNIQUE**: No duplicate values allowed.
  - **NOT NULL**: Data must be present.
  - **PRIMARY KEY**: Unique identifier for table rows.
  - **FOREIGN KEY**: Links to data in another table.
  - **CHECK**: Custom conditions for data.

#### SQL Commands and Migrations
- **List Databases**: Show all databases.
  - Command: `\l` in psql.
- **Connect to Database**: Use to switch databases.
  - Command: `\c <dbname>` in psql.
- **List Tables**: Show all tables in the current database.
  - Command: `\dt` in psql.
- **Create Database/Table**: Define new databases and tables.
  - Example: `CREATE DATABASE <name>;` `CREATE TABLE <name> (...);`.
- **Drop Database/Table**: Remove databases and tables.
  - Example: `DROP DATABASE <name>;` `DROP TABLE <name>;`.
- **Migrations**: Version control for database changes.
  - **Add/Delete**: Add or remove columns or tables.
  - **Up/Down Migration**: Apply or rollback changes.

#### SQL Functions and Clauses
- **SELECT**: Retrieve data from tables.
- **LIMIT**: Restrict the number of rows returned.
- **OFFSET**: Skip a number of rows before returning the data.
- **AS**: Rename columns or tables in the result set.
- **DISTINCT**: Return unique values only.
- **GROUP BY**: Group rows that have the same values in specified columns.
- **HAVING**: Filter groups based on conditions.
- **JOIN**: Combine rows from multiple tables.
  - **INNER JOIN**: Only matching rows.
  - **LEFT JOIN**: All rows from the left table, with matching rows from the right.
  - **RIGHT JOIN**: All rows from the right table, with matching rows from the left.
  - **FULL JOIN**: All rows when there is a match in either table.
- **WHERE**: Filter rows based on conditions.
- **ORDER BY**: Sort rows by specified columns.

#### Views and Indexes
- **Views**: Virtual tables created from queries.
  - **CREATE VIEW**: Define a view.
  - **Materialized View**: Stores results of the view query.
- **Indexes**: Speed up searches by creating a fast lookup.
  - **AUTO_INCREMENT**: Automatically increment values for a primary key.

#### Advanced SQL Functions
- **Aggregate Functions**: Perform calculations on sets of values.
  - Examples: `AVG`, `SUM`, `MIN`, `MAX`, `COUNT`.
- **Scalar Functions**: Operate on individual values.
  - Examples: `UPPER`, `CONCAT`, `SUBSTR`.

#### SQL Commands Categories
- **DDL (Data Definition Language)**: Commands to define database structure.
  - Examples: `CREATE`, `ALTER`, `DROP`, `TRUNCATE`.
- **DML (Data Manipulation Language)**: Commands to manipulate data.
  - Examples: `INSERT`, `SELECT`, `UPDATE`, `DELETE`.
- **DCL (Data Control Language)**: Commands to control access to data.
  - Examples: `GRANT`, `REVOKE`.
- **TCL (Transaction Control Language)**: Commands to manage transactions.
  - Examples: `COMMIT`, `ROLLBACK`, `SAVEPOINT`.
- **DQL (Data Query Language)**: Command to query data.
  - Example: `SELECT`.

#### 3-Schema Architecture
- **Internal Level**: Physical storage structure.
- **Conceptual Level**: Logical structure of the entire database.
- **External Level**: Individual user views.

#### Database Normalization
- **Normalization Levels**: Organize data to reduce redundancy.
  - Levels: 1NF, 2NF, 3NF, BCNF.
- **Anomalies**: Problems like insertion, deletion, or update issues.

#### Relationships and Transactions
- **One-to-One, One-to-Many, Many-to-Many**: Types of relationships between tables.
- **Transactions**: Group of SQL statements executed as a unit.
  - **ACID Properties**: Ensure reliability.
    - **Atomicity**: All-or-nothing.
    - **Consistency**: Data remains consistent.
    - **Isolation**: Concurrent transactions do not interfere.
    - **Durability**: Once committed, changes are permanent.

#### Performance Optimization
- **EXPLAIN**: Analyze query performance.
  - **Heap Scan**: Read rows from a table in no particular order.
  - **Parallel Scan**: Multiple processes scan the table concurrently.

</details>

<details>
<summary><h2>4. Create SQL CRUD REST API with Golang</h2></summary>

#### Project Setup
- **Initialize Project**: Create a new Go module for your project.
  - Command: `go mod init <project-name>`.
- **Dependencies**: Install necessary packages for SQL and HTTP handling.
  - Example: `go get github.com/jackc/pgx/v4` for PostgreSQL.
  - Example: `go get github.com/gin-gonic/gin` for HTTP routing.

#### Database Integration
- **Connect to PostgreSQL**: Use a connection string to link your Go application to the PostgreSQL database.
  - Example: `pgx.Connect(context.Background(), "postgres://username:password@localhost:5432/dbname")`.
- **Database Models**: Define Go structs to map to your database tables.
  - Example:
    ```go
    type User struct {
        ID       int       `json:"id"`
        Username string    `json:"username"`
        Password string    `json:"password"`
    }
    ```
- **ORM Library**: Use GORM or another ORM for easier database interactions.
  - Example: `go get gorm.io/gorm`.

#### CRUD Operations
- **Create (INSERT)**: Add new records to the database.
  - Example:
    ```go
    db.Exec("INSERT INTO users (username, password) VALUES ($1, $2)", username, password)
    ```
- **Read (SELECT)**: Retrieve records from the database.
  - Example:
    ```go
    rows, err := db.Query("SELECT id, username FROM users")
    ```
- **Update (UPDATE)**: Modify existing records in the database.
  - Example:
    ```go
    db.Exec("UPDATE users SET password=$1 WHERE id=$2", newPassword, userID)
    ```
- **Delete (DELETE)**: Remove records from the database.
  - Example:
    ```go
    db.Exec("DELETE FROM users WHERE id=$1", userID)
    ```
- **Validation**: Ensure data is correct before saving to the database.
  - Example: Check for empty fields or invalid data formats.

#### Routing and HTTP Methods
- **Define Routes**: Set up endpoints for each CRUD operation using a web framework like Gin.
  - Example:
    ```go
    router.POST("/users", createUser)
    router.GET("/users/:id", getUser)
    router.PUT("/users/:id", updateUser)
    router.DELETE("/users/:id", deleteUser)
    ```
- **HTTP Methods**: Use appropriate HTTP methods for corresponding operations.
  - **GET**: Retrieve data.
  - **POST**: Create new data.
  - **PUT**: Update existing data.
  - **DELETE**: Remove data.

#### Session Management
- **User Authentication**: Verify users and manage sessions using tokens or sessions.
  - Example: Use JWT (JSON Web Tokens) for stateless authentication.
- **Middleware**: Use middleware to handle authentication and session management.
  - Example: 
    ```go
    router.Use(AuthMiddleware())
    ```

#### Testing
- Use Postman or cURL for manual testing of your API endpoints.

#### Documentation
- **API Documentation**: Use Swagger or similar tools to document your API.
  - Example: Generate API documentation from annotations in your code.
- **Setup Instructions**: Provide clear setup and usage guidelines in your README.
  - Example: Step-by-step instructions for setting up the project and running it locally.

</details>

### [Data Structures and Algorithms Roadmap. 3 Weeks](https://github.com/muhammadfarhankt/Data-Structures-Algoithms-Resource-for-Beginners/)

### [Golang select Statement: A Comprehensive Guide](https://www.scalent.io/golang/golang-select-statement/)

## Must Watch
#### [Concurrency is not Parallelism by Rob Pike](https://www.youtube.com/watch?v=oV9rvDllKEg&t=43s&ab_channel=gnbitcom)

- Crack the top 50 Golang interview questions : https://www.educative.io/blog/50-golang-interview-questions

- https://medium.com/@nur_islam/go-golang-quick-recap-before-an-interview-abbc27cc2ac0/ 
- https://levelup.gitconnected.com/how-to-run-goroutines-in-a-sequence-6f3c729b13ec

