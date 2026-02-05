# 📘 Content Management Systems (CMS) Lab Manual
## 🧪 Lab 01: Introduction to CMS & WordPress Environment

![WordPress Status](https://img.shields.io/badge/WordPress-v6.x-blue?style=flat-square&logo=wordpress)
![Server](https://img.shields.io/badge/Local_Server-XAMPP-orange?style=flat-square&logo=apache)

---

## 🔹 Overview
This repository contains the documentation for setting up a local development environment to manage website content using **WordPress**.

* **Duration:** 2–3 Hours
* **Objectives:** Understand CMS practical terms, set up XAMPP, install WordPress, and master the basic workflow (**Login → Create → Publish**).

---

## 🛠️ Software & Tools Required
- **Local Server:** XAMPP (Apache & MySQL)
- **CMS:** WordPress (Latest Version)
- **Browser:** Google Chrome / Firefox
- **Database Manager:** phpMyAdmin

---

## 🧪 Lab Tasks & Step-by-Step Instructions

### Task 1: Identify Popular CMS Platforms
Identified the following platforms:
1. WordPress
2. Joomla
3. Drupal
4. Shopify
5. Magento

### Task 2: Install Local Server (XAMPP)
1. Download from [apachefriends.org](https://www.apachefriends.org).
2. Install with default settings and open the **XAMPP Control Panel**.
3. Start **Apache** and **MySQL**.
4. Verify by visiting `http://localhost`.

### Task 3: Download & Extract WordPress
1. Download the ZIP from [wordpress.org](https://wordpress.org).
2. Extract and move the folder to: `C:\xampp\htdocs\wordpress`.

### Task 4: Create Database
1. Go to `http://localhost/phpmyadmin`.
2. Create a new database named: **`cms_lab`**.

### Task 5 & 6: Install WordPress & Create Admin
1. Navigate to `http://localhost/wordpress`.
2. **Database Credentials:**
   - **DB Name:** `cms_lab`
   - **Username:** `root`
   - **Password:** *(leave empty)*
3. **Site Details:**
   - **Title:** CMS Lab Website
   - **Admin User:** `admin`
   - **Admin Pass:** `[Your Strong Password]`

---

## 🖥️ Dashboard Navigation & Workflow
| Menu Item | Purpose / Description |
| :--- | :--- |
| **Dashboard** | Overview of site activity and updates. |
| **Posts** | Create and manage blog entries (Dynamic content). |
| **Pages** | Create static content (e.g., About Us, Contact). |
| **Appearance** | Customize the site design and themes. |
| **Plugins** | Add new features and functionalities. |
| **Settings** | Configure site title, URL, and permalinks. |

### Tasks 8, 9 & 10: Content Creation
- **Post:** Created "My First CMS Post" under the Posts menu.
- **Page:** Created an "About Us" static page.
- **Theming:** Installed and activated a new theme via **Appearance → Themes**.

---

## 🔚 Conclusion
After completing this lab, the foundational environment for CMS management is ready. I have successfully mastered local server configuration, database linking, and the initial setup of a WordPress site.

---

## 📅 Next Lab Preview (Week 2)
- [ ] CMS Architecture deep-dive.
- [ ] Understanding Themes vs. Plugins.
- [ ] Configuring User Roles and Permissions.

