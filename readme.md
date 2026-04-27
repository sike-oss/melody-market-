#  MelodyMarket — Premium Musical Instruments Store

A fully functional full-stack e-commerce landing page built for a 
premium musical instruments brand. Designed with a dark luxury 
aesthetic and powered by Firebase Firestore as the backend database.

##  Live Demo
https://melody-store.netlify.app/?fbclid=PAVERFWARcdBhleHRuA2FlbQIxMABzcnRjBmFwcF9pZA8xMjQwMjQ1NzQyODc0MTQAAacZzzcAKzAazcH3Gz4U8SCxNgG67kM1P0cZ2vQIBCUmMI-tdXjH_nXRlXHiFg_aem_6C2YuVM17oQ940eXfE6hqw

## Features

-  **Shopping Cart** — Slide-out cart drawer with quantity 
  controls and live price calculation
-  **Checkout System** — Customer detail form that saves 
  orders to Firestore with full item breakdown
-  **Contact Form** — Functional enquiry form that stores 
  messages in Firestore with timestamps
-  **Admin Panel** — Password-protected dashboard to view 
  all orders and customer enquiries in real time
-  **Premium UI** — Dark theme with red accents, smooth 
  animations, custom cursor, scroll reveals, and mobile 
  responsive design
-  **No Backend Server** — Entirely serverless using 
  Firebase Firestore as the database

##  Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 & CSS3 | Structure and styling |
| Vanilla JavaScript | All interactivity and logic |
| Firebase Firestore | Cloud NoSQL database |
| Google Fonts | Bebas Neue, Cormorant Garamond, DM Sans |
| Font Awesome 6 | Icons throughout the UI |
| Unsplash | Product and hero images |

## 📁 Project Structure

melodymarket/
├── index.html        # Main store page
├── admin.html        # Admin panel (password protected)
└── SETUP_GUIDE.md    # Firebase setup instructions

##  Database Collections

- `orders` — Stores customer details, purchased items 
   array, total amount, and timestamp
- `contact_enquiries` — Stores name, email, subject, 
   message, and timestamp

##  Getting Started

1. Clone the repository
2. Create a Firebase project at console.firebase.google.com
3. Enable Firestore Database
4. Paste your firebaseConfig into index.html and admin.html
5. Open index.html in your browser

##  Admin Access

Navigate to admin.html and enter the admin password 
to view all orders and enquiries.

##  Screenshots


##  Author
Built by Imran Munge 