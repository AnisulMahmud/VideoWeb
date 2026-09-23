# VideoWeb

VideoWeb is a database-driven video-streaming web application developed as a third-year university database course project.

The application was built with core PHP, MySQL, JavaScript, AJAX, HTML, and CSS. It demonstrates server-side development, relational database design, user authentication, content management, search functionality, and frontend–backend integration.

## Key Features

### User Features

* User registration, login, and logout
* User profile management
* Browse movies, television series, and videos
* View content organised by categories and genres
* Search for available movies, series, and videos
* Access content details and video-playback pages
* Update account information
* Delete a user account

### Content-Management Features

* Add movies, series, videos, and categories
* Update existing content information
* Delete content from the catalogue
* Store and manage user and content data
* Organise videos by genre and category

## Technology Stack

* **Backend:** PHP
* **Database:** MySQL
* **Frontend:** HTML, CSS, JavaScript
* **Asynchronous Requests:** AJAX

## Project Structure

```text
VideoWeb/
├── ajax/              # AJAX request handlers
├── assets/            # CSS, JavaScript, images, and frontend resources
├── entities/          # Content-related components
├── includes/          # Reusable PHP components and configuration
├── Category.php       # Category-related functionality
├── entity.php         # Content-entity functionality
├── index.php          # Application landing page
├── login.php          # User authentication
├── logout.php         # User logout
├── register.php       # User registration
├── profile.php        # User-profile management
├── search.php         # Content search
├── movies.php         # Movie catalogue
├── shows.php          # Television-series catalogue
├── watch.php          # Video-playback page
├── categories.sql     # Category database schema and data
├── entities.sql       # Content-entity schema and data
└── videos.sql         # Video schema and data
```

## Running the Project Locally

### Prerequisites

Install a local PHP and MySQL environment such as:
* XAMPP

### Installation

1. Clone the repository:
```bash
git clone https://github.com/AnisulMahmud/VideoWeb.git
```
2. Move the project folder into your local server directory, such as `htdocs` when using XAMPP.
3. Start Apache and MySQL.
4. Create a new MySQL database.
5. Import the provided SQL files:
```text
categories.sql
entities.sql
videos.sql
```
6. Update the project’s database connection settings with your local database name, username, password, and host.
7. Open the application in your browser:
```text
http://localhost/VideoWeb
```

## Skills Demonstrated

This project provided practical experience with:

* Server-side application development using PHP
* Relational database design with MySQL
* User authentication and session management
* SQL queries and CRUD operations
* Form handling and input processing
* Search and content-filtering functionality
* AJAX-based frontend–backend communication
* Structuring and maintaining a multi-page web application

## Project Context
VideoWeb was created as an academic project to apply database and web-development concepts in a complete application. It is maintained as a portfolio project and is not intended for production use.
