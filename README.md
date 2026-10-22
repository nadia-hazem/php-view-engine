# PHP View Engine

Part of the **PICTELLE PHP Starters** collection.

Built on top of the **PHP MVC Starter**.

This project extends the MVC foundation by introducing a simple and reusable view engine using pages, partials and a centralized rendering system.

---

## Features

- Built on top of PHP MVC Starter
- Modern PHP 8+
- Lightweight MVC architecture
- Centralized render() method
- Data passing from controllers to views
- Reusable partials
- Clean project structure
- PSR-4 autoloading
- Vanilla PHP (no framework)

---

## Project Structure

```text
php-view-engine/
│
├── public/
│   └── index.php
│
├── routes.php
│
├── src/
│   ├── Controllers/
│   ├── Core/
│   └── Views/
│       ├── pages/
│       └── partials/
│
├── vendor/
├── composer.json
└── README.md
```

---

## Requirements

* PHP 8.2 or higher
* Composer
* Apache (or equivalent web server)

---

## Installation

Clone the repository

```bash
git clone https://github.com/your-username/php-view-engine.git
```

Install dependencies

```bash
composer install
```

Configure your local web server so that the **public/** directory is the document root.

---

## How it works

Controllers prepare the data and call a single `render()` method.

The render method:

- extracts the data passed by the controller
- loads the shared header
- displays the requested page
- loads the shared footer

Views remain focused on presentation while reusable interface components are stored as partials.

---

## Philosophy

This project intentionally keeps the view engine simple.

Instead of relying on external template engines, it demonstrates how reusable views can be built with native PHP using a clean MVC architecture.

The objective is to understand how controllers, views and reusable components interact before introducing more advanced rendering techniques.


---

## Roadmap

### Foundation Series

* ✅ #1 MVC Starter

* ✅ #2 CRUD

* ✅ #3 View Engine

* 🟩 #4 Route Parameters

---------------------

### Advanced Series

* ⬜ Authentication

* ⬜ Dashboard

* ⬜ Upload Images

* ⬜ Search & Autocomplete

* ⬜ Pagination

* ⬜ Membership

* ⬜ Calendar

* ⬜ Reservation

* ⬜ Comments
---

## Learning Goals

This repository is part of a collection of educational templates built for **Pictelle**, an independent digital craft workshop.

Each template focuses on understanding a specific aspect of web development while remaining practical enough to be reused in real projects.

---

## License

MIT License.
