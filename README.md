Here's a revised and shortened version of the README file with the updated content:  
 Live Project on Vercel -- https://event-management-platform-4a77syhxl-siddharaj-yadavs-projects.vercel.app/
---  
 
<div align="center">
  <br />
    <a href="" target="_blank"> 
      <img src="https://github.com/SidharajYadav/Event-management-platform/blob/main/public/assets/images/Event-Home.jpg" alt="Project Banner">
    </a>
  <br />

## ⚙️ Tech Stack

- Node.js
- Next.js
- TypeScript
- TailwindCSS
- Stripe
- Zod
- React Hook Form
- Shadcn
- Uploadthing

## 🔋 Features

- **Authentication with Clerk:** Secure user management.
- **Event CRUD:** Create, read, update, and delete events.
- **Related & Organized Events:** Display related events and organize user-created events.
- **Search & Filter:** Find events with robust search functionality.
- **Dynamic Categories:** Add new event categories seamlessly.
- **Stripe Integration:** Secure payments and order management.

## 🤸 Quick Start

**Prerequisites**

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

**Clone and Install**

```bash
git clone https://github.com/your-username/your-project.git
cd your-project
npm install
```

**Set Up Environment Variables**

Create a `.env` file and add:

```env
#NEXT
NEXT_PUBLIC_SERVER_URL=

#CLERK
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_CLERK_WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

#MONGODB
MONGODB_URI=

#UPLOADTHING
UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

#STRIPE
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
```

**Run the Project**

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view the project.

Feel free to update or adjust this as needed for your project!
