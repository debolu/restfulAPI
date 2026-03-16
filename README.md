# restfulAPI
A Postman collection for testing the  restful-api.dev  REST API, covering CRUD operations on product objects with both happy-path and negative test scenarios including authentication, validation, and error handling.


This repository contains a Postman collection for interacting with and testing the 
restful-api.dev
 public REST API. It covers the full lifecycle of product object management — from fetching public and authenticated resources to creating, updating, partially updating, and deleting objects.

The collection includes both positive and negative test cases, such as:

Accessing authenticated endpoints with valid, invalid, and missing API keys
Adding products with missing or incorrectly typed fields
Performing full and partial updates with incomplete or malformed payloads
Deleting existing and non-existent objects
Authentication is handled via an x-api-key header, configurable through collection variables (baseURL, baseKey).
