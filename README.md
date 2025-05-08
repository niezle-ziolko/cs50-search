# CS50 Project 0 – Google Search

This is a clone of Google's core search interfaces: Standard Search, Image Search, and Advanced Search. The project was created for CS50’s Web Programming with Python and JavaScript course and implements the required frontend logic using HTML, CSS, and JavaScript, alongside external resources loaded via CDN.

## 🗂️ Project Structure
The project contains three main HTML pages, each corresponding to a core Google service:

```
cs50-search/
├── index.html              # Google Search
├── image.html              # Google Image Search
├── advanced.html           # Google Advanced Search
├── styles.css              # Central stylesheet
├── script.js               # Optional JavaScript functionality
└── README.md
```

All pages share a consistent navigation layout and visual design inspired by the original Google interface.

## ✅ Features Overview

This section summarizes each feature implemented in the application.

### 🔍 Google Search
  - **Search Input**:
   - Centered on the page.
   - Rounded corners for a polished look.
   - "Google Search" and "I'm Feeling Lucky" buttons placed beneath the search bar.

  - **Navigation**:
    - Links to Image Search and Advanced Search are located in the top-right corner.
  
  - **Functionality**:
    - When a user enters a query and clicks "Search", they are redirected to Google’s official search results for that query.
    - Clicking "I'm Feeling Lucky" redirects the user directly to the top search result.

### 🖼️ Google Image Search
  - **Image Search Page**:
    - Provides a similar layout to the standard search page.
    - Input field and search button are centered.
    - Upon submitting a query, the user is redirected to the corresponding Google Images results.

  - **Navigation**:
    - Top-right corner includes a link back to the main search page.

### ⚙️ Advanced Search
  - **Form Fields**:
    - The page includes labeled input fields for:
      - All words
      - Exact phrase
      - Any of the words
      - None of the words
    - Fields are vertically stacked and left-aligned for clarity.
  
  - **Search Button**:
    - A prominently styled "Advanced Search" button (blue background, white text).
    - On click, redirects to a Google results page based on advanced query parameters.

  - **Navigation**:
    - Top-right corner includes a link back to the main search page.

### 🧩 Additional Features
  - **Virtual Keyboard**:
    - Users can type search queries using an on-screen keyboard for accessibility or convenience.

  - **Voice Search**:
    - Enables voice input through supported browsers using the Web Speech API.

  - **Google Lens Support**:
    - Includes a button to upload or link to an image for reverse searching using Google Lens.
    - Redirects to Google’s visual search interface with the image preloaded.

  - **Localization Info**:
    - Displays the user’s detected country/region on the main search page.

## 🚀 Demo
You can view a working version of the project here:
👉 `https://search-8dm.pages.dev/`

Video walkthrough of the specification:
🎥 `https://youtu.be/sLuKh2eZEbg`

## 📜 Certification
This project was submitted as part of the CS50’s Web Programming with Python and JavaScript course offered by Harvard University.
Upon successful completion, I was awarded a certificate, which is available here:

🎓 [View Certificate](https://certificates.cs50.io/6f5116d0-882d-4fc1-9dc6-0c96c5d4c7b1.pdf)