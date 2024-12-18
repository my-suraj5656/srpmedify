Medify - Medical Center Slot Booking Platform
A React-based web application that allows users to find medical centers in the USA by state and city, book appointments, and manage their bookings. Designed to provide a seamless and responsive user experience, the platform is a comprehensive solution for medical appointment scheduling.

🌟 Features
Landing Page
Navigation Bar: Quick access to sections like "Find Doctors," "Hospitals," "Medicines," and more.
Search Section: Dropdowns for selecting state and city, fetching data from APIs, and displaying available medical centers.
Search Results Page
Medical Center Listings: Displays a list of centers in the selected location with essential details.
Book Appointment: Option to book an appointment directly from the listings.
Booking Interface
Calendar View: Users can select an appointment date within a one-week time frame from today.
Time Slot Selection: Displays available slots for the chosen date.
My Bookings Page
Booking Management: Displays a list of all user bookings with details like:
Medical Center Name
Appointment Date & Time
Center Address and Rating
Responsive Design
Fully responsive across devices, adhering to the Figma design guidelines.
Carousel Integration
Carousels implemented using the Swiper library for enhanced visual appeal and functionality.
🚀 Live Demo
Deployed Link: Medify on Vercel
(Replace # with your Vercel deployment link)

📚 Tech Stack
Frontend: React.js, Material-UI
State Management: React State and Props
Data Persistence: LocalStorage
Carousel: Swiper Library
API Integration: Fetch API
Deployment: Vercel
🖼️ Figma Design
You can find the design specifications on Figma.
(Replace # with the Figma link provided in the assignment.)

📡 Backend API Endpoints
The backend API is hosted at MedData Backend.
Below are the available endpoints used in the application:

Get All States
GET https://meddata-backend.onrender.com/states

Get Cities of a Particular State
GET https://meddata-backend.onrender.com/cities/:state
Example: https://meddata-backend.onrender.com/cities/Alaska

Get Medical Centers by State and City
GET https://meddata-backend.onrender.com/data?state=<state>&city=<city>
Example: https://meddata-backend.onrender.com/data?state=Alaska&city=SOLDOTNA