## Resources for tech
  - Next.js - A quick overview and crash course: https://nextjs.org/learn

  - Prisma - ORM to interact with database: https://www.prisma.io/

  - Optional - tRPCs + @tanstack/react-query - a thin type-safe wrapper for full-stack applications: https://trpc.io/docs

  - Databases: 
    + Local/development: sqlite
    + Production: free tiers available to choose from - plannetscale (https://planetscale.com/), supabase (https://supabase.com/), (https://neon.tech/).

  - Authentication: Either store users details in local db and/or using 3rd party authentication.
    + Local db: NextAuth v5 (https://authjs.dev/getting-started/introduction)
    + 3rd party: Clerk (https://clerk.com/), kinde (https://kinde.com/), auth0 (not recommended for project of this size)
  
  - Optional - Pro/Paid version with Stripe: https://stripe.com/en-nz

  - Deploying site: Vercel is the easiest & free host (Next.js is made by vercel team so it extremely easier). 

  - Optional - Real-time update feature: involving websocket/socket.io (https://socket.io/). This won't work on Vercel. MVP can be deployed first and an additional back-end server can be added if real-time features are needed.

  - UI libraries: wide range to choose from: shadcn-ui (recommended, easier to use and modify https://ui.shadcn.com/), charkra-ui (https://chakra-ui.com/), ant-design (https://ant.design/). Tailwind will be compulsory.

  - Additional packages: zod, framer-motion, ...
