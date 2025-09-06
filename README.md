🚌 BusBooker

BusBooker is a user-friendly and reliable bus ticket booking platform designed to make travel comfortable and hassle-free. Search, book, and manage bus journeys with ease, with instant confirmations, secure payments, and 24/7 support.

✨ Features
🧑‍💻 User-Facing

Book Your Bus Journey – Easily search and book buses between cities.

Popular Routes – View most traveled routes with durations and ticket prices.

My Bookings – Track and manage all your bookings in one place.

Admin Panel – Manage routes, tickets, and bookings efficiently.

💡 Benefits

🔒 Safe & Secure – Verified operators and secure payment system.

💰 Best Prices – Compare prices and get the best deals.

⚡ Instant Booking – Immediate confirmation for tickets.

🕒 24/7 Support – Assistance available round the clock.

📁 Project Structure
BusBooker/
├── index.html            # HTML entry point
├── vite.config.ts        # Vite configuration
├── tailwind.config.js    # Tailwind CSS configuration
├── package.json          # NPM dependencies and scripts
├── src/
│   ├── app.tsx           # Root component
│   ├── main.tsx          # Project entry point
│   ├── index.css         # Global CSS
│   └── pages/
│       └── Index.tsx     # Home page logic
├── components/           # shadcn/ui components (@/components/ui)

🎨 Styling

Global styles: src/index.css or create new CSS files.

Use Tailwind CSS classes for styling.

Import reusable components from @/components/ui.

⚙️ Development
Install Dependencies
pnpm i

Add Dependencies
pnpm add <dependency_name>

Start Development Server
pnpm run dev


Runs the project locally for development and preview.
🛠 Technologies Used

React + TypeScript

Vite – Development and build tooling

Tailwind CSS – Styling

shadcn/ui – Reusable UI components

📄 License

This project is open-source and available for personal and commercial use.

Build for Production
pnpm run build
