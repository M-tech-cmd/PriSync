PriSync 🔍📉

Smart E‑commerce Price Tracking & Product Intelligence Platform

PriSync is a modern web scraping and price‑monitoring application built with Next.js 16 and Bright Data’s Web Unlocker. It helps users make informed purchasing and business decisions by tracking e‑commerce products (such as Amazon listings), notifying users when prices drop, and alerting competitors when products go out of stock — all powered by automated cron jobs.

Designed with scalability, clean architecture, and reusability in mind, PriSync demonstrates a production‑ready approach to web scraping, data persistence, and automated notifications.

🌟 Key Capabilities

📉 Track product price changes in real time

📦 Monitor stock availability

📬 Automated email alerts for price drops & restocks

⏱️ Scheduled scraping via cron jobs

🧱 Clean, reusable, and scalable code architecture

⚙️ Tech Stack

Framework: Next.js 16

Scraping Infrastructure: Bright Data (Web Unlocker)

HTML Parsing: Cheerio

Email Service: Nodemailer

Database: MongoDB

UI Components: Headless UI

Styling: Tailwind CSS

🔗 Bright Data: https://brdta.com/

🔋 Features

🖼️ User Interface

Header with Carousel – Visually engaging hero section highlighting key benefits

Responsive Design – Optimized for all screen sizes

🔎 Product Scraping

Amazon Product Scraping – Paste a product URL to fetch live data

Scraped Products Dashboard – View all tracked products at a glance

Detailed Product Pages – Displays product image, title, price history, stock status, and metadata

🔔 Tracking & Alerts

Track Product Modal – Users opt‑in by providing an email address

Email Notifications – Alerts for:

Price drops

Back‑in‑stock updates

Lowest price reached

⚙️ Automation

Cron Jobs – Periodic scraping to keep product data fresh

Background Jobs – Automated monitoring without manual input

🤸 Quick Start

Follow the steps below to run PriSync locally.

✅ Prerequisites

Ensure you have the following installed:

Git

Node.js (18+ recommended)

npm

📥 Clone the Repository

git clone https://github.com/M-tech-cmd/PriSync.git

📦 Install Dependencies

npm install

🔐 Environment Variables

Create a .env file in the project root and add the following:

# SCRAPER
BRIGHT_DATA_USERNAME=
BRIGHT_DATA_PASSWORD=

# DATABASE
MONGODB_URI=

# EMAIL (OUTLOOK)
EMAIL_USER=
EMAIL_PASS=

Populate these values with your own credentials.

▶️ Run the Development Server

npm run dev

Open http://localhost:3000 in your browser.

🚀 Production‑Ready Highlights

Modular and maintainable architecture

Secure scraping via proxy‑based infrastructure

Scalable background automation

Real‑world e‑commerce use cases

PriSync is suitable for price tracking tools, competitor monitoring platforms, and market intelligence systems.

👨‍💻 Author

M-tech-cmdFull‑Stack Developer | Web Scraping & SaaS Builder

