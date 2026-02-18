# Image Searcher Platform

The **Image Searcher Platform** is a web-based application that allows users to search for high-quality images using keywords. It fetches real-time image results from the **Unsplash API** and displays them in a clean, responsive grid layout.

This project is built using **HTML, CSS, and JavaScript** and focuses on learning how to work with third-party APIs, handle user input, and dynamically update the DOM.

---

## Features

- Search for images using keywords  
- Fetches real-time results from the Unsplash API  
- Displays images in a responsive grid layout  
- “Show More” button to load additional images  
- Clean and beginner-friendly user interface  

---

## language Used

- **HTML** – Structure of the application  
- **CSS** – Styling and layout  
- **JavaScript** – API handling, DOM manipulation, and logic  
- **Unsplash API** – Image data source  

---

## How It Works

1. The user enters a keyword into the search input  
2. A request is sent to the Unsplash API using `fetch()`  
3. The API returns images related to the keyword  
4. Images are dynamically added to the page  
5. Clicking **Show More** loads additional results  

---

## Personal Reflection

### What this project is  
This project is an image search application that connects a front-end interface to a real-world API. It demonstrates how external data can be fetched and displayed dynamically in a web application.

### Why I made it  
I created this project to practice working with APIs and improve my understanding of asynchronous JavaScript. I wanted hands-on experience building something interactive rather than a static webpage.

### How I made it  
I first built the structure and layout using HTML and CSS. Then, I used JavaScript with `async/await` to fetch image data from the Unsplash API. I implemented pagination so users can load more images without refreshing the page and dynamically updated the DOM to display results.

### What I struggled with  
Managing API pagination and clearing previous search results were challenging at first. I also had to debug issues related to asynchronous data fetching and DOM updates.

### What I learned  
Through this project, I learned:
- How to work with third-party APIs  
- How to use `async/await` for asynchronous operations  
- How to dynamically manipulate the DOM  
- How to manage application state such as search keywords and page numbers  
- How to build a more interactive user experience  
