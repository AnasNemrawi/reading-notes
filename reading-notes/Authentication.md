# Data Modeling

## Securing Passwords
Q1: Explain to a non-technical friend how you would safely hash and store a password.

Safely hashing and storing a password involves converting it into a unique and scrambled string using a special function. We add a random value called a salt to make it even more secure. Then we store this scrambled version in a protected database, never the actual password.

Q2: What is Bcrypt?

Bcrypt is an algorithm designed to securely scramble passwords. It makes it difficult for attackers to guess passwords by slowing down their attempts.

Q3: Why might you use something like Bcrypt?

We use something like Bcrypt to make it hard for attackers to crack passwords. It slows down their guessing attempts and adds a unique value to each password, making it more secure.

## Basic Authentication
Basic Authentication is a simple method to provide credentials in an HTTP request. The necessary properties in the request header are the "Authorization" field, which indicates the request requires authentication, and the "Authorization" value in the format "Basic [credentials]". The username:password pair in Basic Auth is encoded using Base64.

## OWASP auth cheatsheet
1. Define the authentication process to a non-technical recruiter.
Authentication is the process of verifying a user's identity when accessing a system. It involves the user providing their username and password, which are checked against stored records. If the credentials match, the user is granted access; otherwise, access is denied.

2.How should your error messaging respond (both HTTP and HTML)? Why?
Error messaging should be handled in both HTTP responses and HTML pages to provide clear information to users. In HTTP responses, status codes like 404 or 500 indicate the type of error, while reason phrases give a brief description. This helps clients and developers understand the issue. In HTML error pages, user-friendly messages should be displayed. Handling error messaging in both HTTP responses and HTML pages, users can have a better understanding of encountered errors, developers can diagnose issues efficiently, and the overall user experience can be improved.

