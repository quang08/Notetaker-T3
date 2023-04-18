Full-stack notetaker app built with [T3 Stack](https://create.t3.gg/). Customize your topic and write your notes with built in Markdown editor!

- **Framework**: [Next.js](https://nextjs.org/)
- **Database**: [Supabase](https://supabase.com/)
- **Type-safety**: [tRPC](https://trpc.io/)
- **ORM**: [Prisma](https://prisma.io/)
- **Authentication**: [NextAuth (AuthJS)](https://next-auth.js.org/)
- **Deployment**: [Vercel](https://vercel.com)
- **Styling**: [DaisyUI](https://daisyui.com/)

# Home signed out
<img width="1349" alt="Home1" src="https://user-images.githubusercontent.com/84165564/232741531-69443502-e638-4a5f-8aaa-f2521f3ef265.png">

# Home signed in with GitHub
<img width="1349" alt="Home2" src="https://user-images.githubusercontent.com/84165564/232741524-194159da-41fd-49b4-a9eb-96da3e5f4fb9.png">

# Markdown editor
<img width="1349" alt="Markdown1" src="https://user-images.githubusercontent.com/84165564/232741517-91b04f0d-7bd2-481e-b364-fd1b527677eb.png">

<img width="1349" alt="Markdown2" src="https://user-images.githubusercontent.com/84165564/232741507-38e0d23e-4484-4961-8bf1-f6453da1a90e.png">

<img width="1349" alt="Markdown3" src="https://user-images.githubusercontent.com/84165564/232741480-9e325094-6afb-43b6-b8ca-3931f3ddda7e.png">

To run this project, you will need to add the following environment variables to your `.env` file

```bash
# Database URL for Prisma
DATABASE_URL=

# Clerk for auth
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

```

## Run Locally

Clone the project

```bash
  git clone https://github.com/quang08/Notetaker-T3.git
```

Go to the project directory

```bash
  cd Notetaker-T3
```

Install dependencies

```bash
  npm install
```

Apply migrations to database

```bash
  npx prisma db push
```


Start the server

```bash
  npm run dev
```
