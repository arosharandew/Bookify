# 🎟️ Bookify – Event Booking System UI

A modern, responsive event booking website prototype for discovering and reserving tickets to concerts, movies, and conferences. Built with **HTML, CSS, and JavaScript**, this project showcases a clean user interface with interactive components like seat selection, ticket counters, and dynamic filtering.



---

## 🚀 Live Demo

[View Live Demo](https://arosharandew.github.io/Bookify/) 

---

## 📌 Features

- **Responsive Design** – Works on desktops, tablets, and mobile devices  
- **Event Categories** – Browse events by genre: Concerts, Movies, Conferences  
- **Interactive Booking Flows:**  
  - **Movies:** Select location, date, time, and choose seats from an interactive grid  
  - **Concerts:** Adjust ticket quantities for General and VIP categories with live total calculation  
  - **Conferences:** Increment attendee count with instant price update  
- **Filter Panel** – Filter events by genre, price range, location, and date (UI demo)  
- **Past Events Slider** – Auto-scrolling carousel of previous events  
- **Testimonials Section** – Customer reviews with star ratings  
- **Authentication Pages** – Sign Up, Login, and Profile pages (UI only)  
- **About & Contact Pages** – Informative static pages with responsive image slider on About page  

---

## 🛠️ Technologies Used

- **HTML5** – Semantic markup  
- **CSS3** – Flexbox, Grid, animations, and responsive design  
- **JavaScript (ES6)** – DOM manipulation, event handling, dynamic content rendering  
- **Font Awesome** – Icons for contact details  
- **Google Fonts** – *Fredoka One* for playful headings  

---

## 📁 Project Structure

```
bookify-event-platform/
│
├── index.html              # Home page with event listings and filters
├── about.html              # About Us page with image slider
├── contact.html            # Contact page (placeholder)
├── signup.html             # Sign Up page (UI)
├── login.html              # Login page (UI)
├── profile.html            # User profile page (UI)
├── movie.html              # Movie booking page (seat selection)
├── concert.html            # Concert booking page (ticket quantities)
├── conference.html         # Conference booking page (attendee count)
│
├── styles.css              # Global styles
├── about.css               # Additional styles for about page
├── concert.css             # Styles for concert/conference pages
├── movie.css               # Styles for movie booking page
│
├── script.js               # Home page logic (tabs, search, filters)
├── past-events.js          # Past events slider data & rendering
├── movie.js                # Seat grid generation and booking logic
├── concert.js              # Ticket counter and total calculation
├── conference.js           # Attendee counter and total calculation
│
└── assets/                 # Images, icons, etc.
    ├── filter.png          # Filter button icon
    ├── p1.jpg, p2.jpg...  # Slider images for About page
    └── ...                 # Other images
```

---

## 🧑‍💻 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Edge, Safari)

### Run Locally

1. Clone the repository:
```bash
git clone https://github.com/arosharandew/Bookify.git
cd Bookify
```

2. Open any HTML file:
- Double-click `index.html`  
- OR serve the folder using a live server (e.g., VS Code Live Server extension)

---

## 🔧 Customization

- **Event Data:** Modify arrays in `script.js`, `past-events.js`, `concert.js`, `movie.js`, `conference.js` to update titles, prices, images, etc.  
- **Styling:** Adjust colors, fonts, and layouts in the respective CSS files  
- **Seat Layout:** Change grid dimensions in `movie.js` via `rows` and `cols` variables  

---

## 📸 Screenshots

| Home Page | Movie Booking |
|-----------|---------------|
| ![Home Page](assets/home.png) | ![Movie Seat Selection](assets/movie.png) |

| Concert Booking | About Page |
|-----------------|------------|
| ![Concert Tickets](assets/concert.png) | ![About Slider](assets/about.png) |

---


## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## ✨ Acknowledgements

- Design inspired by modern event ticketing platforms  
- Icons by **Font Awesome**  
- Fonts by **Google Fonts**  
- Built with ❤️ by **Arosha Fernando**
