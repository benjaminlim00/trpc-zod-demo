# TRPC-Zod integration

This repo aims to demostrate type safe code using the combination of TRPC to share types across FE and BE and Zod for schema validation

## TRPC

TRPC is a tool that helps developers work with APIs in a type-safe manner. It stands for "Type-safe Remote Procedure Call." In simpler terms, it allows the frontend (the part of a web application that you see in your browser) and the backend (the server that handles requests and data) to communicate in a way that avoids common errors and bugs related to data types.

Imagine you're sending a request from your browser to a server. TRPC ensures that the data you send and receive is well-defined and matches your expectations. This means you're less likely to encounter issues where the server expects one type of data, but the browser sends a different type, leading to errors in your application.

## Zod

Zod is a library that helps with data validation. It allows you to define the structure and rules for your data. When data is sent or received in your application, Zod ensures that it conforms to the rules you've set. In other words, it's like having a set of quality checks for your data.

For instance, if you're expecting a user's email address, you can use Zod to define the format that an email should have. If the data doesn't match that format, Zod will flag it as invalid, helping you catch and handle incorrect or malicious data.

In summary, TRPC ensures safe and well-defined communication between your frontend and backend, while Zod helps you ensure the quality and validity of the data your application works with. Both of these tools are important for building reliable and secure web applications.
