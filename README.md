# Todo App

A full-stack Todo application built with Next.js, React, and PostgreSQL.

## Features

- Add, edit, and delete tasks
- Mark tasks as complete or incomplete
- Smooth animations using Framer Motion
- Responsive design with Tailwind CSS
- Server-side rendering with Next.js
- PostgreSQL database integration using Prisma ORM

## Technologies Used

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Prisma](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [Radix UI](https://www.radix-ui.com/)

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm or yarn
- PostgreSQL database

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yuvateja2003/Todo-App
   cd todo-app
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up your environment variables:
   Create a `.env` file in the root directory and add your PostgreSQL connection string:
   ```
   DATABASE_URL="postgresql://username:password@localhost:5432/todo_db?schema=public"
   ```

4. Run database migrations:
   ```
   npx prisma migrate dev
   ```

5. Start the development server:
   ```
   npm run dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Deployment

This project can be easily deployed on [Vercel](https://vercel.com/). Follow these steps:

1. Push your code to a GitHub repository.
2. Log in to your Vercel account.
3. Click on "New Project" and select your GitHub repository.
4. Configure your environment variables (DATABASE_URL) in the Vercel dashboard.
5. Deploy the project.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.