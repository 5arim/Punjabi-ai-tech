**Punjabi AI Tech Website**

**Overview**

This is the source code for the Punjabi AI Tech website, developed by Optimal Soft Sol. The website is designed to promote artificial intelligence education for young learners in Punjab, offering resources, courses, and interactive tools in both English and Urdu. It features a modern, responsive design with bilingual support, a chatbot integration, and various sections to engage users with AI learning opportunities.
Features

**Bilingual Support:**

Seamlessly toggle between English and Urdu using a language switcher, with right-to-left (RTL) text alignment for Urdu.
Responsive Design: Built with Tailwind CSS and custom styles for optimal viewing on desktops, tablets, and mobile devices.

**Interactive Elements:**

Hover effects on buttons and cards for enhanced user interaction.
Pulsing animation for call-to-action (CTA) buttons.
Expandable resource cards and FAQ sections.


**Chatbot Integration:**

Uses Tidio for real-time user support, with language-specific welcome messages.
Form Submissions: Integrated with Google Forms for subscription and contact form submissions, with confirmation alerts.
Social Media Links: Connects to YouTube, Facebook, and WhatsApp for user engagement.
Custom Styling: Features a gradient theme inspired by Punjab’s vibrant culture, with smooth scrolling and section dividers.

**Project Structure**

**File: index.html**

The main HTML file containing the website structure, styles, and JavaScript functionality.


**Assets:**

Punjabi-AI-logo.jpg: Logo used for the favicon and About section.
sample ai.jpg: Sample AI-generated design displayed in the AI & Graphic Design section.


**External Dependencies:**

Tailwind CSS (v2.2.19) via CDN for responsive styling.
Google Fonts (Poppins and Noto Nastaliq Urdu) for typography.
Icons8 for social media icons.
Tidio Chat for chatbot functionality.



**Setup Instructions**

**Clone or Download:**

Download the index.html file and associated assets (Punjabi-AI-logo.jpg, sample ai.jpg).
Ensure assets are placed in the same directory as index.html or update the file paths in the code if hosted elsewhere.


**Hosting:**

Deploy the index.html file and assets to a web server (e.g., Netlify, Vercel, or a local server like XAMPP).
No server-side processing is required as the site is static.


**Dependencies:**

The website uses CDNs for Tailwind CSS and Google Fonts, so an internet connection is required for these resources to load.
Tidio Chat requires an active Tidio account and the provided script URL (wcxtkszlh5zh5bq9ht196wfl2jmqpfy7.js). Replace it with your own Tidio script if needed.


**Testing:**

Open index.html in a modern browser (Chrome, Firefox, Safari) to test functionality.
Verify language toggle, form submissions, and chatbot integration.
Test responsiveness on various screen sizes using browser developer tools.



**Usage**

**Language Toggle:**

Click the language button in the header to switch between English and Urdu. The site dynamically updates text, placeholders, and text alignment.
**Navigation:**

Use the sticky navigation bar to jump to sections (About, Courses, AI & Design, Blog, Contact, FAQ, Resources, Socials).

**Forms:**

**Notify Me:**

In the Courses section, users can submit their email to receive updates via a Google Form.

**Contact Us:**

Users can send messages with their name, email, and message via a Google Form.


**Chatbot:**

The Tidio chatbot initializes with a welcome message based on the selected language.

**Resources:**

Click resource cards to reveal additional details about AI tools and tutorials.

**Customization**

**Update Content:** Modify text in data-en and data-ur attributes to change English and Urdu content.
**Styling:** Adjust the .gradient-bg colors or other CSS properties in the <style> section to match your branding.
**Assets:** Replace Punjabi-AI-logo.jpg and sample ai.jpg with new images, ensuring correct file paths.
**Tidio Chat:** Update the Tidio script URL in the <script> tag to point to your Tidio project ID.
**Forms:** Update the Google Forms URLs in the action attributes of the <form> tags to your own form endpoints.

**Known Issues**

**Asset Availability:** Ensure Punjabi-AI-logo.jpg and sample ai.jpg are accessible on the server, or the images will not display.
**Tidio Dependency:** The chatbot requires an active Tidio account. If the Tidio script fails to load, the chatbot functionality will be unavailable.
**Internet Dependency:** CDNs and external links (e.g., Google Fonts, Tailwind CSS) require an internet connection.

**Contact**

**Developed by Optimal Soft Sol. For support or inquiries, contact:**

Phone: +923040809061
Email: [sarimhayatofficial@gmail.com]

**License**

© 2025 Punjabi AI Tech. All rights reserved.
