# DIGITAL_MAGAZINE_MANAGEMENT_SYSTEM

_The case study is a digital magazine management system that allows users to manage magazines, articles, and subscriptions. The system has four main tables: Magazine, Article, Subscription, and User._

Setup Instructions
Prerequisites:
**Java Development Kit (JDK) installed**
**MySQL Server installed**
**MySQL JDBC driver**

The Magazine Table has the following columns:
**- magazine_id (Primary Key)**
**- title**
**- genre**
**- publication_frequency**
**- publisher**

The Article Table has the following columns:
**- article_id (Primary Key)**
**- magazine_id (Foreign Key references Magazine Table)**
**- title**
**- author**
**- content**
**- publish_date**

The Subscription Table has the following columns:
**- subscription_id (Primary Key)**
**- user_id (Foreign Key references User Table)**
**- magazine_id (Foreign Key references Magazine Table)**
**- subscription_date**
**- expiry_date**
**- status (active/inactive)**

The User Table has the following columns:
**- user_id (Primary Key)**
**- username**
**- email**
**- date_of_birth**
**- registration_date**

The system has the following functionalities:
- Magazine Management:
    - Add a new magazine
    - View magazine details
    - Update magazine information
    - Delete a magazine
- Article Management:
    - Add a new article to a magazine
    - View article details
    - Update article information
    - Delete an article
- Subscription Management:
    - Subscribe to a magazine
    - View subscription details
    - Update subscription information
    - Cancel a subscription



The requirements of the case study are:
- Develop a menu-based console application using Core Java.
- Use JDBC for interactions with the MySQL database.
- Implement menu options for managing magazines, articles, and subscriptions.
- Ensure that the application updates subscription statuses and handles user, magazine, and article data efficiently.
- Handle exceptions effectively and provide user-friendly error messages.
- Ensure the application code is clean, well-documented, and follows standard coding conventions.
