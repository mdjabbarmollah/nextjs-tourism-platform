# Next.js Tourism Platform

## Project Overview
A scalable full-stack tourism and travel booking website where users can browse destinations and manage their tour bookings seamlessly.

## Live Preview
![Project Screenshot](./screenshot (2).png)

## Main Technologies Used
- Next.js (App Router)
- TypeScript
- MongoDB
- Tailwind CSS

## Key Features
- Server-side rendering for optimal SEO and fast load times.
- Dynamic routing for individual travel destinations.
- Secure database integration for managing user bookings.

## Dependencies
- `next`: ^14.1.0
- `react`: ^18.2.0
- `mongoose`: ^8.2.0
- `tailwindcss`: ^3.4.1

## Core Code Snippets (For Reference)

**`package.json`**
```json
{
  "name": "nextjs-tourism-platform",
  "version": "1.0.0",
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start"
  },
  "dependencies": {
    "next": "^14.1.0",
    "react": "^18.2.0",
    "mongoose": "^8.2.0"
  }
}
```

**`app/page.tsx`**
```tsx
export default function Home() {
  return (
    <main className="flex min-h-screen flex-col items-center justify-center p-12 bg-slate-50">
      <h1 className="text-4xl font-extrabold text-slate-800 mb-4">Explore The World</h1>
      <p className="text-lg text-slate-600">Your ultimate platform for booking premium travel destinations.</p>
    </main>
  );
}
```

## Local Run Guidelines
To run this project locally on your machine, follow these steps:
1. Clone the repository: `git clone <your-repo-link>`
2. Navigate to the folder: `cd nextjs-tourism-platform`
3. Install dependencies: `npm install`
4. Set up `.env` file with your MongoDB URI: `MONGODB_URI=your_database_url`
5. Start the development server: `npm run dev`

## Relevant Links
- **Live Link:** [https://demo-tourism-nextjs.com](https://demo-tourism-nextjs.com)
- **Repository Link:** [https://github.com/mdjabbarmollah/nextjs-tourism-platform](https://github.com/mdjabbarmollah/nextjs-tourism-platform)

