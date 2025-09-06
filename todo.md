# Bus Ticket Booking Web Application - MVP Implementation Plan

## Core Files to Create/Modify (Max 8 files):

### 1. **src/pages/Index.tsx** - Home Page
- Bus search form (source, destination, date)
- Hero section with modern design
- Quick search functionality

### 2. **src/pages/BusList.tsx** - Available Buses
- Display search results
- Bus cards with details (timing, price, seats available)
- Filter options (price, departure time, bus type)

### 3. **src/pages/SeatSelection.tsx** - Seat Selection
- Interactive seat map (2x2 layout)
- Real-time seat availability
- Seat pricing and selection logic

### 4. **src/pages/BookingConfirmation.tsx** - Booking Summary
- Passenger details form
- Payment integration (demo)
- Booking confirmation with PNR

### 5. **src/pages/Profile.tsx** - User Dashboard
- User authentication forms (Login/Signup)
- Booking history
- Profile management

### 6. **src/pages/AdminDashboard.tsx** - Admin Panel
- Bus management (Add/Edit/Delete)
- Route management
- Booking analytics

### 7. **src/lib/store.ts** - State Management
- User authentication state
- Booking flow state
- Bus data and seat availability

### 8. **src/components/Layout.tsx** - App Layout
- Navigation header
- Authentication status
- Route protection

## Key Features Implementation:
- ✅ Modern responsive UI with Tailwind CSS
- ✅ Role-based authentication (User/Admin)
- ✅ Bus search and filtering
- ✅ Interactive seat selection
- ✅ Booking flow with PNR generation
- ✅ Payment integration (demo)
- ✅ Admin panel for management
- ✅ Mobile-friendly design

## Mock Data Structure:
- Users: { id, name, email, role, phone }
- Buses: { id, name, type, totalSeats, amenities }
- Routes: { id, source, destination, duration, distance }
- Schedules: { id, busId, routeId, departureTime, arrivalTime, price, date }
- Bookings: { id, userId, scheduleId, seats, pnr, status, totalAmount }