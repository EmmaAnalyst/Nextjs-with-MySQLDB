# Synthesis of Next.js and Azure Database for MySQL

This Next.js project uses Prisma to connect to an Azure-hosted MySQL database and Tailwind CSS for styling.

## Prerequisites
Install Node.js and create an Azure MySQL Flexible Server if you don’t have one. Set up a new database called products via the Azure portal.

Use create-next-app to bootstrap a Next.js project, then download and place the SSL certificate in the prisma folder to enable secure MySQL connections.

Create a MySQL connection string using your server credentials and add it as an environment variable in Vercel. 
Push your schema to the database and seed the data with Prisma.

Run the app locally using npm run dev and deploy it to Vercel for production.