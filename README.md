<div align="center">
  <h3 align="center">Log It</h3>

  <p align="center">
    This is a full-stack project exercise using NEXT.JS as the framework.
  </p>
</div>
<hr>

 ## 💡 Key Features
* Landing page
* Auth for Organizational and Personal Workspace Usage Rights.
* Fetching Unsplash image API for random beautiful cover images.
* CRUD Operations for Boards, Lists, and Cards.
* Activity log for Card and entire organization
* rename, drag & drop reorder and copy functions of List and Card
* Board limit for every organization
* Stripe subscription for each organization to unlock unlimited boards

 ## 🛠 Tech Stack 
![nextjs logo](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white&style=for-the-badge)
  ![typescript logo](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white&style=for-the-badge)
  ![tailwindcss logo](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=black&style=for-the-badge)
  ![prisma logo](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white&style=for-the-badge)
  ![mysql logo](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white&style=for-the-badge)

## 📖 Libraries
* <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRdVEuXbieiDLdzyT-lHa1wtFVPK2ONT5utgQ&usqp=CAU" alt="Clerk" width="14"/>  **Clerk** : Simplify user authentication and identity management with customizable features.
* <img src="https://images.crunchbase.com/image/upload/c_pad,h_170,w_170,f_auto,b_white,q_auto:eco,dpr_1/iidhf24ewhnqtjgrrfbp" alt="Planetscale" width="14"/>  **Planetscale** : MySQL-compatible database.
* <img src="https://avatars.githubusercontent.com/u/139895814?s=280&v=4" alt="Shadcn" width="14"/>  **Shadcn** : Enhance UI development with a collection of reusable components for improved code reusability.
* <img src="https://b.stripecdn.com/site-statics-srv/assets/assets/img/v3/home/twitter-80afaafee00af0bc21d345164a2a9bb6.png" alt="Stripe" width="14"/>  **Stripe** : Securely accept and manage payments online with this robust payment processing platform.
* <img src="https://avatars.githubusercontent.com/u/72518640?s=200&v=4" alt="Tanstack" width="14"/>  **Tanstack react query** : Streamline data fetching, caching, and updates in React applications for efficient state management.
* <img src="https://uploads-ssl.webflow.com/5b0c471ddb589cf22d4477a4/5cd716028463a5a1d1b1e73d_unsplash-app-icon-2.png" alt="Unsplash" width="14"/>  **Unsplash** : Get the largest free collection of high-quality images using the Image api.
* <img src="https://seeklogo.com/images/Z/zod-logo-B57E684330-seeklogo.com.png" alt="Zod" width="14"/>  **Zod** : Ensure data integrity and type safety with TypeScript-first schema declaration and validation.
* <img src="https://img.stackshare.io/service/11559/zustand.png" alt="Zustand" width="14"/>  **Zustand** : Simplify global state management in React applications with a minimalistic API.

### Setup .env file:
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

DATABASE_URL=
NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=

STRIPE_API_KEY=
NEXT_PUBLUC_APP_URL=http://localhost:3000
STRIPE_WEBHOOK_SECRET=
```

### Install packages:
```bash
npm i
```

### Run the development server:
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
