# MKF Cafe Website - Project Report

---

## 1. Title Page

**Project Title:** MKF Cafe Website
**Tagline:** Brewed Fresh, Served Warm
**Project Type:** Restaurant/Cafe Website
**Date:** 2025
**Location:** M.M. Alam Road, Gulberg III, Lahore, Punjab, Pakistan

---

## 2. Table of Contents

1. Title Page
2. Table of Contents
3. Project Overview
4. Objectives of the Website
5. Tools & Technologies Used
6. Website Structure (6 Pages Overview)
7. Design Approach
8. Responsiveness & Theme
9. CSS Animations Used
10. Page-wise Screenshots
11. Group Roles & Contributions
12. Challenges Faced
13. Conclusion

---

## 3. Project Overview

MKF Cafe is a fully functional multi-page website designed for a local cafe based in Lahore, Pakistan. The website was built using basic HTML and CSS and serves as the complete digital presence of the cafe. It allows customers to explore the menu, make table reservations, view upcoming events, learn about the cafe, and get in touch with the team.

The website consists of 6 pages, all linked together through a consistent navigation menu. The design reflects the warm, welcoming atmosphere of the cafe through its color scheme, layout, and content.

---

## 4. Objectives of the Website

The main objectives of building this website were:

1. To create an online presence for MKF Cafe
2. To allow customers to make reservations online
3. To display the full food and beverage menu with prices
4. To promote upcoming cafe events
5. To provide contact information and location details
6. To share the story and background of the cafe
7. To ensure the website works on all devices including mobile phones, tablets, and laptops

---

## 5. Tools & Technologies Used

**Languages Used:**
- HTML5 - for building the structure of all pages
- CSS3 - for styling, layout, and responsive design

**External Services:**
- Formspree.io - used to receive reservation form submissions via email

**Development Tools:**
- Notepad / VS Code - for writing the code
- Google Chrome - for testing and previewing the website

**Design Resources:**
- Google Fonts - for typography
- Unsplash - for placeholder food and cafe images

---

## 6. Website Structure (6 Pages Overview)

**Page 1 - Home Page (index.html)**
This is the main landing page of the website. It displays four cafe images at the top followed by the cafe name and tagline. It has five golden buttons that link to all other pages of the website.

**Page 2 - Menu Page (menu.html)**
This page displays the full cafe menu divided into three sections: Starters, Main Course, and Desserts. Each item shows the food name, description, and price. Food images are displayed at the top of the page.

**Page 3 - Reservation Page (reservation.html)**
This page contains an online booking form. Customers can fill in their name, email, phone number, date, time, number of guests, and any special requests. The form is connected to Formspree to send reservation details directly to the cafe email.

**Page 4 - Events Page (events.html)**
This page lists all upcoming events at the cafe. Each event shows the date, title, time, description, and location inside the cafe. Events include Live Jazz Night, Christmas Brunch, Coffee Tasting Workshop, New Year Special, Open Mic Night, and Cooking Class.

**Page 5 - Contact Page (contact.html)**
This page provides complete contact details including address, phone number, email, and opening hours. It also includes a message form for customers to send queries directly to the cafe.

**Page 6 - About Us Page (about.html)**
This page tells the story of how MKF Cafe started. It shares the journey from a small idea among friends to a full cafe. It includes a cafe image and a button to return to the home page.

---

## 7. Design Approach

**Color Scheme:**
- Black (#000000) - used for headers, navigation, and buttons
- Whitesmoke (#f5f5f5) - used for page backgrounds
- Golden Yellow (#f4d03f) - used for home page buttons
- Brown (rgb(128, 91, 24)) - used for menu headings and event dates
- Beige - used as background for the menu page
- Light Gold (rgb(201, 165, 99)) - used for food descriptions

**Typography:**
- Times New Roman - used for main titles to give a classic cafe feel
- Arial - used for body text for clean readability

**Layout:**
- Clean and simple vertical layout
- White card boxes for menu items and events
- Centered content for headings and titles
- Consistent header and footer on all pages

**Navigation:**
- Home page uses large golden buttons for navigation
- All other pages use a dark grey top navigation bar with white links

---

## 8. Responsiveness & Theme

The website is fully responsive and adjusts its layout based on the screen size of the device being used.

**Desktop (above 1024px):**
Images display side by side, full navigation bar visible, large font sizes

**Tablet (768px to 1024px):**
Images resize, font sizes reduce slightly, layout adjusts to fit medium screens

**Mobile (below 768px):**
Images stack vertically and become full width, font sizes reduce, navigation links stack or shrink, all content fits within the small screen without horizontal scrolling

This was achieved using CSS media queries like:
@media (max-width: 768px) and @media (max-width: 480px)

---

## 9. CSS Animations Used

**Hover Effects on Buttons:**
- Home page golden buttons slightly enlarge when hovered using transform: scale(1.05)
- Button background color changes on hover for all pages
- Navigation links change color when hovered

These simple CSS effects improve user experience and make the website feel more interactive without using JavaScript.

---

## 10. Page-wise Screenshots

**Home Page:** Shows four food images, large MKF Cafe title, tagline, and five golden navigation buttons

**Menu Page:** Shows food images at top, three white boxes for Starters, Main Course, and Desserts with item names, descriptions, and prices

**Reservation Page:** Shows black header, navigation bar, and a clean booking form with all required fields and a submit button

**Events Page:** Shows six event cards each with a brown date badge, event title, time in orange, description, and location

**Contact Page:** Shows contact info boxes with location, phone, email, opening hours table, and a message form at the bottom

**About Us Page:** Shows cafe image, large "Our Journey" title, four paragraphs of cafe story, and a golden back to home button

---

## 11. Group Roles & Contributions

**Member 1:** Built the Home Page and About Us Page, handled overall design consistency

**Member 2:** Built the Menu Page and structured all food items and pricing

**Member 3:** Built the Reservation Page and integrated Formspree for email submissions

**Member 4:** Built the Events Page and Contact Page, handled responsive design

*(Update with actual names and roles of your group members)*

---

## 12. Challenges Faced

**Challenge 1 - Image Paths:**
Original images used local file paths from the computer which did not work on the web. We fixed this by using a proper images folder with relative paths.

**Challenge 2 - Layout Overlapping:**
The original menu page had overlapping sections caused by negative margins. We fixed this by removing negative margins and using a simple vertical layout.

**Challenge 3 - Responsiveness:**
Making the website work on mobile phones was difficult at first. We solved this by adding CSS media queries that adjust font sizes, image sizes, and layout for smaller screens.

**Challenge 4 - File Naming:**
Some files had spaces in their names like "Page 1.html" and "About Us.html" which caused linking issues. We fixed this by renaming files to index.html and about.html.

**Challenge 5 - Form Submission:**
HTML forms alone cannot send emails. We solved this by connecting the reservation form to Formspree which handles email delivery for free.

**Challenge 6 - Navigation Consistency:**
Different pages had different navigation styles. We standardized the navigation menu across all pages so it looks and works the same everywhere.

---

## 13. Conclusion

The MKF Cafe website is a complete, functional, and well-designed 6-page website built entirely with HTML and CSS. It successfully meets all its objectives by providing an online platform for customers to explore the cafe, make reservations, view events, and get in touch.

The project helped us understand the fundamentals of web development including HTML structure, CSS styling, responsive design, form creation, and multi-page linking.

The website is clean, easy to maintain, beginner-friendly, and ready to be hosted online. With future improvements such as JavaScript interactivity, a photo gallery, and social media integration, the website can be further enhanced.

**MKF Cafe - Brewed Fresh, Served Warm**

---

*Project Submitted by: M.Maaz Gul*
*Date: 2025*