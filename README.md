
# T3 Test
T3 Test is a repository to test a project bootstrapped with a simple command create-t3-app, aiming to provide a robust foundation for building modern web applications. It integrates various technologies to streamline development and enhance user experience.

## Technologies Used
- Next.js: Next.js is a React framework providing capabilities such as server-side rendering, static site generation, and routing, making it ideal for building fast and scalable web applications.

- NextAuth.js: NextAuth.js is an authentication library for Next.js projects, offering easy-to-use authentication solutions with support for various authentication providers and authentication flows.

- Prisma: Prisma is a modern database toolkit for TypeScript and Node.js, enabling easy database access, migrations, and type-safe querying.

- Drizzle: Drizzle is an ORM (Object-Relational Mapping) library for Node.js, providing a seamless interface for interacting with databases and simplifying data manipulation tasks.

- Tailwind CSS: Tailwind CSS is a utility-first CSS framework, offering pre-defined utility classes to rapidly build custom designs without writing traditional CSS styles.

- tRPC: tRPC is a TypeScript framework for building RPC (Remote Procedure Call) APIs, allowing for efficient communication between client and server.

## Getting Started
To get started with T3 Test, follow these steps:

1. Clone the repository:

```
git clone https://github.com/ViniciusCestarii/t3-test.git
```
2. Install dependencies:

```
cd t3-test
npm install
```

3. Configure environment variables:

Create a .env file in the root directory and provide the necessary environment variables. Refer to .env.example for required variables and their format.

4. Create database using Docker:
```
docker compose up
```

5. Update database schema with Drizzle:
```
npm run db:push
```

4. Start the development server:

```
npm run dev
Open your browser and navigate to http://localhost:3000 to view the application.
```

