COMPANY : CODTECH IT SOLUTIONS

NAME : Bushapogu Lisa Susana

INTERN ID : CT04DK165

DOMAIN : Java Programming

DURATION : April15th, 2025 to May 15th, 2025.

MENTOR : NEELA SANTOSH KUMAR

DESCRIPTION:

Creating a REST API client using Java is a practical way to learn about how modern applications communicate over the web. A REST (Representational State Transfer) API allows different software systems to interact using standard HTTP methods such as GET, POST, PUT, and DELETE. This project involves developing a Java application that acts as a client, connecting to a public REST API—such as a weather service—and retrieving relevant data. The client should be capable of sending HTTP requests to the server, receiving responses, and then parsing the received data, which is typically formatted in JSON (JavaScript Object Notation). The application will ultimately display the parsed information in a structured and user-friendly format, such as formatted console output or a graphical interface.

To implement this, the Java program must utilize libraries that support HTTP communications and JSON processing. Java offers several tools for these purposes. For HTTP requests, developers can use built-in classes from the java.net.http package (available from Java 11 onward) or external libraries like Apache HttpClient or OkHttp. For parsing JSON, popular choices include the org.json library, Google's Gson, or Jackson. The program begins by constructing a request URL that includes any required parameters such as API keys or location queries. Then, it sends an HTTP GET request to the API endpoint and waits for a response. Upon receiving the response, the program checks the HTTP status code to ensure the request was successful (typically a 200 OK response), and then reads the JSON data from the response body.

Once the JSON data is available, the next step is to parse it. JSON objects can be deeply nested and may contain arrays, so the parser must navigate through the structure carefully to extract relevant fields, such as temperature, humidity, wind speed, and weather descriptions. These extracted values are stored in appropriate Java data structures or objects for easier manipulation and display. Depending on the design, the data might be printed in a clean tabular format in the console or used to update elements in a GUI built with libraries like JavaFX or Swing.

This kind of project teaches several important software development skills. It provides experience with client-server architecture, network programming, and JSON handling. Additionally, it promotes understanding of error handling, as the application must gracefully manage potential issues like network failures, invalid responses, or malformed data. For further enhancement, the application can include features such as caching recent queries, allowing user input for custom city searches, or displaying data in a more visual format.

The final deliverable is a complete Java application that demonstrates the ability to consume and process data from a public REST API. It should showcase clean and modular code with proper use of classes and exception handling. This project is not only a solid exercise in Java programming but also a stepping stone toward building more advanced web-connected applications. It exemplifies how real-world services can be integrated into software to provide dynamic, real-time information to users.








