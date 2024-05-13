# Golang Developer Roadmap

## 1. Learn the Golang fundamentals

- Go Tour: Start with the official Go Tour to get familiar with the language syntax and features. [Visit A Tour of Go to begin.](https://go.dev/tour/welcome/1/)
- W3Schools: Utilize W3Schools' Go tutorial for a structured introduction to the language. Visit W3Schools Go Tutorial to get started.[https://www.youtube.com/watch?v=un6ZyFkqFKo&ab_channel=freeCodeCamp.org]
- Your Master Plan to Learn Golang Fast and Deep (2024 Edition) : https://medium.com/p-society/master-plan-to-learn-golang-edbf85c7ae83
- Video Tutorials: If you prefer video learning, check out this tutorial from Freecodecamp: Go Programming – Golang Course with Bonus Projects.[https://www.youtube.com/watch?v=un6ZyFkqFKo&ab_channel=freeCodeCamp.org] (Watch the first few chapters up to slices).
- Learn by doing. Install golang on your system or start by doing Golang Online compilers.[https://www.programiz.com/golang/online-compiler/]
- GeeksforGeeks: Dive deeper into Golang fundamentals on [Geeksforgeeks](https://www.geeksforgeeks.org/golang/) for comprehensive learning.
- Short Variable Declaration: Utilize the short declaration syntax (:=) to declare variables without assigning garbage values. Defaults to zero (0) or false for boolean.
- Loop Types: Master different loop types including range loops and understand loop approaches (while, do while, infinite loop).
- Arrays vs Slices: Differentiate between arrays and slices, focusing on capacity management and slice behavior on overflow. Understand that slices are built on top of arrays and provide a more flexible way to work with data collections. When a slice's capacity is exceeded, Go automatically doubles the underlying array's size to accommodate additional elements. This dynamic resizing ensures efficient memory usage and allows slices to grow dynamically as needed.
- Strings in Go: Learn about the string data type, byte vs rune, immutability, and string manipulation techniques.
- Functions: Explore the flexibility of functions in Go, including returning multiple data types and variadic functions.
- Initialising a project. `go mod init <project name>`
- Maps and Structs: Explore Go's map and struct data types, including declaration, manipulation, size, and capacity.

## 2. Now it's time to learn Golang special features

- Understanding Go: Explore the reasons behind Go's creation and its design philosophy.
- _(underscore) indentifier.
- Packages and Modules: Understand Go's package system, including importing/exporting packages. Practice writing functions in other packages and importing them. Remember to capitalize function names for exporting.
- Error Handling: Treat errors as a data type and learn effective error handling techniques.
- Understand following new vs make, GO Path and GO Root
- Goroutines and Channels: Learn about Go's powerful concurrency features, including goroutines and channels.
- OOP Concepts in Go: Understand how Go implements object-oriented programming (OOP) concepts and whether it follows OOP or procedural programming (POP) paradigms.
- Defer: Understand the defer statement and its role in handling function execution flow.
- Concurrency vs Parallelism: Differentiate between concurrency and parallelism in the context of Go programming.

## 3. Learn Web Fundamentals with Golang
### (Research & Learn following topics in detail. Watch videos & Read documentations / tutorial sites)
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

## 4. Practice Project: Login System with Session Management

### Develop a Server-Side Login Page:

#### View Engines:
- With view engines, developers can create dynamic web pages by injecting data from the server-side application logic into predefined HTML templates. This separation of concerns between data and presentation enhances code maintainability and scalability in web projects.
- Explore view engines and their role in generating dynamic HTML content for web pages.
- Understand how view engines like HTML templates or server-side rendering frameworks work.
- Go's standard library provides the html/template package, which offers a robust template engine for generating HTML content.
- Server-side rendering frameworks like Gin, Echo, or Fiber often integrate seamlessly with view engines, allowing developers to define routes and render templates in a unified manner.
- View engines in Go typically follow the Model-View-Controller (MVC) pattern, where templates serve as the "view" layer responsible for presenting data to users.
- Enhances code maintainability by separating data and presentation concerns.
  
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


- Crack the top 50 Golang interview questions : https://www.educative.io/blog/50-golang-interview-questions
