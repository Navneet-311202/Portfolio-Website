# Portfolio Website

A modern, responsive portfolio website built with React, Express.js, and PostgreSQL.

## Features

- Responsive design with Tailwind CSS
- Smooth scroll animations
- Interactive project showcase
- Skills visualization
- Contact form
- Resume section
- Database integration for dynamic content

## Local Development

1. Clone the repository
2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
Create a `.env` file with the following:
```
DATABASE_URL=your_postgresql_database_url
```

4. Run database migrations:
```bash
npm run db:push
```

5. Start the development server:
```bash
npm run dev
```

## Deployment

### Option 1: Deploy on Replit (Recommended)

1. Fork this Repl
2. Click the "Run" button
3. Your site will be live at your-repl-name.username.repl.co

### Option 2: Manual Deployment

1. Build the project:
```bash
npm run build
```

2. The built files will be in the `dist` directory
3. Deploy the contents to your preferred hosting platform

## Downloading the Project

1. From Replit:
   - Click on the three dots menu in the files panel
   - Select "Download as zip"

2. Using the files locally:
   - Extract the downloaded zip file
   - Follow the Local Development instructions above

## Technologies Used

- React
- Express.js
- PostgreSQL
- Tailwind CSS
- TypeScript
- Drizzle ORM
- Framer Motion
- shadcn/ui

## Structure

- `/client` - Frontend React application
- `/server` - Backend Express.js server
- `/shared` - Shared types and schemas
