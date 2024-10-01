# Jobify

Jobify is a comprehensive job tracking application designed to help you manage your job search journey. It enables users to keep track of:

+ All the jobs you’ve applied for
+ The number of interview requests you’ve received
+ Rejections, if any

## Features

+ **Application Tracker:** Monitor all your job applications in one place.
+ **Interview Requests:** Keep track of the interview opportunities you’ve received.
+ **Rejections:** Log and track any rejections to stay informed of your application status.
+ **Monthly Stats:** A statistics feature displaying the number of applications you’ve sent each month for the past year.

**Usage:**

1. **Create `.env.local` file:**
   ```bash
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key  
2. **Create `.env` file:**
   ```bash
   DATABASE_URL=postgresql://your_user:your_password@your_host:your_port/your_database
  **Installation:**
   ```bash
DATABASE_URL=postgresql://your_user:your_password@your_host:your_port/your_database
````
**Start:**
   ```bash
npm run dev 
````
+ you can try to seed an example of database 
   ```bash
   node prisma/seed
