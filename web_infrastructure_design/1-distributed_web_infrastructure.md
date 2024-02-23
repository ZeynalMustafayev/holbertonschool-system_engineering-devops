Definition:

Distributed web infrastructure refers to the concept of distributing the components of a website across multiple servers or devices, rather than hosting everything on a single server. This can improve the performance and reliability of a website, as well as making it more resilient to outages or attacks. In a distributed web infrastructure, individual components of a website, such as the database, web server, and application server, can be spread across multiple devices, and requests to the website can be routed to the appropriate device based on factors such as the user’s location or the type of request. This can help to improve the speed and scalability of a website, as well as making it more resilient to failure.


Distributed Web Infrastructure
A load-balancer (HAproxy)

Load balancers are used to distribute network traffic across multiple servers. This helps to ensure that no single server becomes overwhelmed with requests, improving the overall performance and reliability of the system. HAProxy, or High Availability Proxy, is a popular open-source load balancer that is often used in high-traffic web environments. It can be configured to distribute incoming requests to a group of servers, based on a variety of factors such as the server’s current load or the geographic location of the client making the request. By using a load balancer like HAProxy, organizations can improve the availability and performance of their web applications, allowing them to handle a larger number of requests without downtime or other performance issues.

Set of Application Files (Your Code Base)

A set of application files, or code base, is a collection of source code files that make up the core functionality of a software application. These files are typically written in a programming language, such as Java or Python, and are organized into different modules or components that perform specific tasks within the application. The code base is a crucial part of any software development project, as it defines the functionality and behavior of the application.

Database (MySQL)

MySQL is a popular and widely-used relational database management system (RDBMS) that uses Structured Query Language (SQL) to manage and manipulate data stored in databases. It is open-source software, which means that it is free to use and distribute. MySQL is known for its reliability, performance, and ease of use, making it a popular choice for a wide range of applications and websites. Some of the key features of MySQL include the ability to store and manage large amounts of data efficiently, support for multiple storage engines, and a robust security model.

How a Database Primary-Replica (Master-Slave) Cluster Works

In a database primary-replica cluster, one database server is designated as the primary server and is responsible for handling read and write operations. The other database servers, known as replica servers, continuously replicate the data from the primary server, ensuring that they always have an up-to-date copy of the data.

When a client wants to read or write data, it sends a request to the primary server. The primary server handles the request and then sends the updated data to the replica servers so that they can update their copies of the data. This ensures that all of the servers in the cluster have the same data, allowing for high availability and fault tolerance.

If the primary server goes down for any reason, one of the replica servers can be promoted to take its place, ensuring that the database remains available and that no data is lost. This makes primary-replica clusters a highly reliable and scalable solution for managing large amounts of data.

Security Issues (no firewall, no HTTPS)

Without a firewall and HTTPS, a website is vulnerable to a number of security risks. A firewall is a security system that monitors and controls incoming and outgoing network traffic based on predetermined security rules. It helps protect a website from malicious attacks by blocking incoming traffic that violates the security rules. HTTPS, on the other hand, is a protocol that encrypts the communication between a website and a user’s web browser, making it more difficult for hackers to intercept and read sensitive information.
