# CMS Lab Journal - WordPress Setup
**Course:** Content Management Systems (CMS)  
**Lab 01:** Environment Setup & WordPress Installation

---

## Project Overview
This repo documents my progress in setting up a local development environment for WordPress. The goal of this first lab was to get a local server running, configure a database, and handle the initial WordPress installation workflow.

* **Completion Time:** ~2.5 Hours
* **Key Goals:** XAMPP configuration, Database management via phpMyAdmin, and basic content publishing.

## Environment & Tools
* **Local Server:** XAMPP (Apache & MySQL)
* **CMS:** WordPress 6.x
* **Database:** MariaDB (via phpMyAdmin)

---

## Lab Implementation Steps

### 1. Local Server Setup (XAMPP)
* Downloaded and installed XAMPP from Apache Friends.
* Initialized **Apache** and **MySQL** services via the Control Panel.
* Verified the local environment by hitting `http://localhost`.

### 2. WordPress Configuration
* **File Management:** Downloaded the WordPress core files and moved the extracted folder to `htdocs`.
* **Database Setup:** Created a new database named `cms_lab` in phpMyAdmin.
* **Installation:** Linked the site to the database using the following local credentials:
    * **DB Name:** `cms_lab`
    * **User:** `root`
    * **Password:** (None)

### 3. Site Admin Details
* **Site Title:** CMS Lab Website
* **Admin Username:** `admin`
* **Access Point:** `http://localhost/wordpress/wp-admin`

---

## Post-Installation Tasks

### Content Management
I tested the core functionality by creating the initial site structure:
1.  **Dynamic Content:** Published a test post titled "My First CMS Post".
2.  **Static Content:** Built an "About Us" page to test page-level attributes.
3.  **Theming:** Browsed the WordPress repository and swapped the default theme to test the rendering engine.

### Dashboard Quick Reference
| Section | Usage |
| :--- | :--- |
| **Posts** | Used for blog entries and dynamic updates. |
| **Pages** | Used for permanent content like "Contact" or "About". |
| **Appearance** | Where I handled theme installation and customization. |
| **Plugins** | Used to extend the site features. |

---

## Takeaways
By the end of this lab, I have a fully functioning local WordPress instance. I now understand the relationship between the file system (`htdocs`), the database (MySQL), and how the CMS bridges them to serve content.

**Next Steps:**
* Exploring CMS architecture.
* Differentiating between Theme and Plugin hooks.
* Managing user permissions.
