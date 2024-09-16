# Care Pulse

Care Pulse is a comprehensive Healthcare Management System enabling patient registration and appointment booking. This system streamlines patient registration, appointment booking, and administrative tasks for healthcare providers.

![Care Pulse](/public/assets/images/care-pulse.png)

## Tech Stack 📚

- **Frontend:**
  - Next.js 14
  - React 18
  - TypeScript
  - Tailwind CSS
  - Shadcn UI
  - React Hook Form
  - Zod
  - TanStack React Table
  - React Dropzone (file upload)
- **Backend:**
  - Appwrite (Backend as a Service)
- **Development Tools:**
  - ESLint 8
  - Prettier (via ESLint config)

## Features 🎉

### Patient Portal

- **Comprehensive Registration System**
  - Detailed medical history forms
  - Family medical history collection
- **Dynamic Appointment Booking**
  - Doctor selection
  - Time slot choosing

### Admin Portal

- **Secure Authentication**
  - Passkey-based login for enhanced security
- **Appointment Management**
  - Schedule new appointments
  - Reschedule existing appointments
  - Cancel appointments as needed
- **Admin Dashboard**
  - Overview of clinic operations

### Notification System

- SMS notifications for appointment updates
  - Confirmation messages
  - Rescheduling notifications

### User Experience

- Responsive design for cross-device compatibility
- Intuitive interface for easy navigation

### Data Management

- Robust data validation
- Secure storage of patient information

## Getting Started 🚀

### Prerequisites

- Node.js
- npm or yarn
- Appwrite account

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/tapadar13/care-pulse.git
   ```

2. Navigate to the project directory

   ```bash
   cd care-pulse
   ```

3. Install dependencies

   ```bash
   npm install
   # or
   yarn install
   ```

4. Set up environment variables
   Create a `.env.local` file in the root directory and add the following variables:

   ```
   PROJECT_ID=your_appwrite_project_id
   API_KEY=your_appwrite_api_key
   DATABASE_ID=your_appwrite_database_id
   PATIENT_COLLECTION_ID=your_patient_collection_id
   DOCTOR_COLLECTION_ID=your_doctor_collection_id
   APPOINTMENT_COLLECTION_ID=your_appointment_collection_id
   NEXT_PUBLIC_BUCKET_ID=your_appwrite_bucket_id
   NEXT_PUBLIC_ENDPOINT=your_appwrite_endpoint
   NEXT_PUBLIC_ADMIN_PASSKEY=your_admin_passkey
   SENTRY_AUTH_TOKEN=your_sentry_auth_token
   ```

5. Run the development server

   ```bash
   npm run dev
   # or
   yarn dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Scripts 📜

- `dev`: Start the development server
- `build`: Build the application for production
- `start`: Start the production server
- `lint`: Lint the codebase

## Contributing 🤝

We welcome contributions to improve the Healthcare Management System. Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
5. Push to the branch (`git push origin feature/AmazingFeature`)
6. Open a Pull Request

## Acknowledgments 🙏

- Special thanks to the creators and maintainers of the following frameworks and libraries:
  - Next.js
  - React
  - TypeScript
  - Tailwind CSS
  - Appwrite
  - React Hook Form
  - Zod
  - Shadcn UI
  - React Dropzone
  - TanStack React Table

---

If you like this project, please consider giving it a star ⭐️
