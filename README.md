# ShopRite Website

## Overview
ShopRite is a responsive e-commerce website designed to provide users with a seamless and accessible shopping experience.  
It features a clean layout, logo branding, a hero banner, product categories, and responsive navigation.

## Part 2 Summary
In Part 2 of the project, the following improvements were made:
- Added an external stylesheet (`css/style.css`) and linked it across all pages.
- Implemented base styles and CSS variables for consistent design.
- Introduced a responsive typography scale and heading styles.
- Developed a flexible layout using CSS Grid with a two-column desktop layout and stacked mobile layout.
- Enhanced navigation to be responsive and accessible.
- Collected and documented screenshots of responsive breakpoints.

## Breakpoints
- **Desktop (≥ 1024px):** Two-column grid layout, horizontal navigation.
- **Tablet (≥ 768px and < 1024px):** Single-column layout with adjusted typography.
- **Mobile (< 768px):** Stacked layout, vertical navigation, and optimized spacing.

## Screenshots
### Desktop
<img width="1919" height="1098" alt="Screenshot 2025-09-25 163054" src="https://github.com/user-attachments/assets/3a36a762-ff10-49f9-aa6e-93f9a2114a5a" />


### Tablet
<img width="1912" height="1090" alt="Screenshot 2025-09-25 162817" src="https://github.com/user-attachments/assets/a0448129-5e0b-46a4-a0a7-3d0092fdc404" />


### Mobile
<img width="1915" height="1096" alt="Screenshot 2025-09-25 162950" src="https://github.com/user-attachments/assets/0fc51fe4-8a30-4911-8901-f04e87eb8ebc" />



## Changelog
See [CHANGELOG.md](CHANGELOG.md) for detailed updates.


1. Lightbox Image Gallery

A lightbox feature was added to the gallery section to allow users to click on any image and view a larger version in a popup overlay.
JavaScript is used to:

Detect when a gallery image is clicked

Open the lightbox overlay

Display the selected image in full size

Close the lightbox when the user clicks the close button or background


Benefit:
This improves user experience by letting visitors view images clearly without 

navigating away from the page.

2. Interactive Google Map

An embedded Google Map was added to the contact page using the Google Maps Embed API.
Users can zoom, move the map, and easily view the business location.

Benefit:
Improves trust and provides users with directions and location information.

3. Search/Filter Function

A dynamic search bar was created on the services page to filter services in real time.
JavaScript listens for user input and hides or shows services depending on the search term.


Benefit:
Makes navigation easier and helps users quickly find the service they want.

4. Form Validation & Enquiry Form Processing

The enquiry form uses both HTML5 validation and JavaScript for enhanced checks.
JavaScript was used to:

Prevent automatic submission

Validate user input

Show a custom confirmation message

Process basic calculations (if required)

Benefit:
Ensures correct input, reduces mistakes, and provides instant feedback to users.

5. Contact Form Email Handling (Formspree Integration)

The contact form was connected to Formspree, a third-party service that handles email submissions.
Since browsers cannot send emails directly, Formspree allows the form to send messages using JavaScript endpoints.

Benefit:
Provides real email functionality without server-side code.

Search Engine Optimization (SEO) Implemented


1. Title Tags

Unique and descriptive title tags were added to every page.
Example:
“Web Design Services | My Company Name”

Purpose:
Helps Google understand the topic of each page.


2. Meta Descriptions

Every page has a custom meta description summarising the page content in 1–2 sentences.

Purpose:

Improves click-through rates on search engine results pages.


3. Heading Structure (H1, H2, H3)

All pages were updated to follow proper heading hierarchy:

Only one H1 per page (main title)

Subsections use H2 and H3


Purpose:
Helps search engines read and prioritise content correctly.

4. Image Optimization

Images were optimized by:


Renaming files (e.g., web-design-service.jpg instead of IMG_099.jpg)

Adding descriptive alt text

Reducing file sizes for faster loading


Purpose:
Improves accessibility, search ranking, and performance.

5. robots.txt

A robots.txt file was created in the root folder to guide search engine crawlers on which pages they may or may not index.

Purpose:
Improves crawler efficiency and site 

visibility.


6. sitemap.xml

A sitemap was created listing all key pages of the website, allowing search engines to discover and index the entire site structure.

Purpose:
Helps improve crawling and SEO performance.


7. Clean & Semantic HTML

Clean file names, proper indentation, and semantic tags (such as <header>, <main>, <section>, <footer>) were used throughout the website.


Purpose:
Makes it easier for search engines to understand the content.

