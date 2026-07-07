# Nilrise Pharma Clone

A responsive pharmaceutical website clone built using **HTML**, **CSS**, and **JavaScript**. The project includes a dashboard-style homepage, product category navigation, a slideshow banner, contact information, doctor contact redirection, and separate catalog pages for dermatology and general antibiotics.

## Project Overview

This project is designed as a basic front-end pharmaceutical company website. It showcases product segments such as **Dermatology**, **General Antibiotics**, and **COVID-19 Care**, with additional contact and inquiry sections.

The website includes:

- A homepage/dashboard with navigation links
- A top contact bar with logo, phone number, and email
- A sticky navigation header
- An automatic image slideshow
- Product category buttons
- Doctor contact form navigation
- Dermatology product catalog page
- General antibiotics information page
- Inquiry and feedback contact section
- Footer with support and back-to-top links

## Pages Included

| File | Description |
|---|---|
| `sample.html` | Main dashboard/homepage of the website |
| `skin.html` | Dermatology and skin care product catalog |
| `ANTIBOTIES1.html` | General antibiotics information page |
| `covid-19.html` | COVID-19 care page linked from dashboard |
| `form-nilrise.html` | Doctor contact form page linked from dashboard |
| `login.html` | Logout redirects to this page |
| `skin.css` | External stylesheet used by the skin care catalog |
| `image.png` | Logo image used in the top bar |
| `image copy.png` | Product image used in the skin care catalog |

## Features

## Homepage

The homepage contains the main layout of the website. It includes a top bar, navigation menu, slideshow, product categories, doctor contact section, and inquiry details.

Key elements:

- **Top Bar:** Displays the Nilrise logo, phone number, and email.
- **Sticky Header:** Remains fixed at the top while scrolling.
- **Navigation Menu:** Links to Home, About Us, Products, Our Networks, and Contact.
- **Refresh Button:** Reloads the current page.
- **Logout Button:** Redirects the user to `login.html`.
- **Image Slideshow:** Displays pharmaceutical-themed images with captions.
- **Product Segment Buttons:** Redirect users to category pages.
- **Doctor Contact Section:** Redirects users to a doctor contact form.
- **Inquiry Section:** Shows contact personnel, phone number, institution, and email.

## Dermatology Catalog

The dermatology page displays skin care and therapeutic products in a card-based grid layout.

Products listed include:

| Product | Category |
|---|---|
| Itrazil Dusting Powder | Antifungal |
| ScabiFight-G Lotion | Anti-Parasitic |
| Zoyclo-M Plus Cream | Multi-Action |
| Zoyclo-M Cream | Anti-Inflam |
| Ketozit-Plus Cream | Antifungal |
| Zoybec-C Cream | Antibacterial |
| Metafresh Mouth Wash | Oral Care |
| Viroglin-400 | Antiviral Oral |
| Moromax Cream | Featured Repair |
| Fusimark Cream | Topical Antibiotic |
| ScabiFight Soap | Medicated Bar |
| Mupizit Ointment | Ointment |

Each product card includes:

- Product name
- Product category tag
- Product description
- Key advantages
- Usage instructions

## General Antibiotics Page

The antibiotics page provides basic information about selected antibiotics.

Medicines included:

| Medicine | Strength |
|---|---|
| Cefixime | 200 mg |
| Amoxicillin | 200 mg |
| Linezolid | 600 mg |

The page includes:

- Antibiotic descriptions
- Common uses
- Important precautions
- Side effects
- Back button navigation
- Footer with contact and back-to-top option

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Styling and layout |
| JavaScript | Slideshow functionality and page navigation |
| Font Awesome | Icons for phone and email |
| External Images | Slideshow and product visuals |

## Folder Structure

```text
Nilrise-Pharma-Clone/
├── sample.html
├── skin.html
├── ANTIBOTIES1.html
├── covid-19.html
├── form-nilrise.html
├── login.htmlsample.html
├── Dermatology Button -> skin.html
├── General Antibiotics Button -> ANTIBOTIES1.html
├── COVID-19 Care Button -> covid-19.html
├── Contact Doctor Button -> form-nilrise.html
├── Logout Button -> login.html
└── Back Buttons -> sample.html
