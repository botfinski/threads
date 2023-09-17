# Threads app

[work in progress]

Made in Next.js + TypeScript, Tailwind and MongoDB. Auth done by Clerk

To run create .env.local file

```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY
CLERK_SECRET_KEY

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

NEXT_CLERK_WEBHOOK_SECRET

MONGODB_URL

UPLOADTHING_SECRET
UPLOADTHING_APP_ID
```

then run

```bash
npm install
npm run dev
```
