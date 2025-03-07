# The Wild Oasis Website

## Description
The Wild Oasis is a user-friendly web application designed for customers to explore, book, and manage cabin stays seamlessly. The platform provides an intuitive interface for browsing available cabins, filtering by capacity, and making reservations. Users can also manage their profiles, including updating personal details and profile photos. The authentication system allows sign-in and sign-up using Google via Next-Auth, ensuring a secure and hassle-free experience.

## Live Demo & Repository
- **Live:** [The Wild Oasis - Live](https://the-wild-oasis-website-sumit-jangra.vercel.app/)
- **GitHub:** [The Wild Oasis - GitHub](https://github.com/SumitNub12/the-wild-oasis-website.git)

## Tech Stack
- **Frontend:** Next.js, Tailwind CSS
- **Authentication:** Next-Auth (Auth.js) with Google OAuth
- **Backend:** Supabase

## Features
- **Cabin Booking:** Users can browse available cabins, view details, and make reservations.
- **Filter by Capacity:** Easily find cabins that match their group size requirements.
- **Edit Profile:** Users can update personal information such as name and profile photo.
- **Authentication:** Google login and sign-up using Next-Auth.

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone [https://github.com/your-repo-link.git](https://github.com/SumitNub12/the-wild-oasis-website.git]
   cd the-wild-oasis-website
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env.local` file in the root directory and add the following environment variables:
   ```env
   SUPABASE_URL=
   NEXTAUTH_URL=
   NEXTAUTH_SECRET=
   AUTH_GOOGLE_ID=
   AUTH_GOOGLE_SECRET=
   ```
4. Run the development server:
   ```sh
   npm run dev
   ```
5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Deployment
This project can be deployed on Vercel, Netlify, or any platform that supports Next.js. Ensure your environment variables are configured correctly.

## Contributing
Feel free to submit issues or pull requests to improve the project.

