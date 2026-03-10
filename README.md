# LMS-FullStack
# LIVE DEMO - https://lms-full-stack-client-pi.vercel.app/

A full-stack Learning Management System (LMS) built with the MERN stack (MongoDB, Express, React, Node.js), featuring course management, student progress tracking, and payment integration.

## Key Features

- **User Authentication**: Secure login and registration using Clerk.
- **Course Management**: Admins can create, update, and manage courses.
- **Student Progress**: Track learning progress and completion status.
- **Payment Integration**: Seamless transactions handled via Stripe.
- **Media Storage**: Image and file uploads managed through Cloudinary.

## Tech Stack

- **Frontend**: React, Vite, Tailwind CSS, Clerk, Axios.
- **Backend**: Node.js, Express, MongoDB (Mongoose), Clerk SDK, Stripe, Cloudinary, Multer, Svix.

## Project Structure

- `/client`: Frontend React application.
- `/server`: Backend Express server.

## Getting Started

### Prerequisites

- Node.js installed.
- MongoDB database (local or Atlas).
- Clerk, Stripe, and Cloudinary API keys.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/vedantpatil182/LMS-FullStack.git
   ```

2. Install dependencies:
   - For Client: `cd client && npm install`
   - For Server: `cd server && npm install`

3. Set up environment variables:
   - Create `.env` files in both `client/` and `server/` directories with your respective API keys and configuration.

4. Run the application:
   - Client: `npm run dev`
   - Server: `npm run server`
