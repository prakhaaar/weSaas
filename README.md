# weSaas

**weSaas** is a modern SaaS (Software as a Service) web application built with Next.js and Prisma, designed to provide scalable and flexible solutions for your business needs.

## Features

- User authentication and authorization  
- Dynamic form creation and submission management  
- Real-time data handling with Prisma and PostgreSQL  
- Responsive UI with Tailwind CSS  
- Easy deployment on Vercel or other cloud platforms

## Tech Stack

- **Frontend:** Next.js, React, Tailwind CSS  
- **Backend:** Node.js, Prisma ORM  
- **Database:** PostgreSQL (hosted on Supabase)  
- **Deployment:** Vercel  

## Getting Started

### Prerequisites

- Node.js (v16 or above)  
- PostgreSQL database or Supabase account  
- Git

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/weSaas.git
   cd weSaas
Install dependencies:

bash
Copy
Edit
npm install
Setup environment variables:

Create a .env file in the root directory and add your database URL:

env
Copy
Edit
DATABASE_URL="your-postgres-connection-string"
DIRECT_URL="your-postgres-direct-connection-string"
Run Prisma migrations:

bash
Copy
Edit
npx prisma migrate dev --name init
Start the development server:

bash
Copy
Edit
npm run dev
Open http://localhost:3000 to view the app.

Prisma Schema
The Prisma schema is defined in prisma/schema.prisma and includes models like Form and Submission to manage forms and their user submissions.

Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

License
This project is licensed under the MIT License.







