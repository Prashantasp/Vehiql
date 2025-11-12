
---

## **Vehiql — AI Car Marketplace —**

```markdown
#  Vehiql — AI Car Marketplace

**Vehiql** is a full-stack **AI-powered car marketplace** built with **Next.js** and **Supabase**.  
It enables users and dealers to **list, search, and manage cars** — including **AI image-based search** for smart vehicle trading.

---

##  Features

-  **AI-powered image-based car search** Upload an image to find similar cars.
-  **AI Car suggestion** based on car details (brand, year, mileage, etc.)
-  **Role-based authentication** using Clerk (User, Dealer, Admin)
-  **10+ dynamic filters** for fast car discovery.
-  **Supabase integration** for database and image storage.
-  Responsive and modern **UI with Tailwind CSS + Shadcn UI**.
-  **Optimized backend** using Prisma ORM.

---

## Tech Stack

**Frontend:** Next.js, Tailwind CSS, Shadcn UI  
**Backend:** Supabase (PostgreSQL), Prisma ORM  
**Auth:** Clerk  
**AI Integration:** Python (Image classification & price prediction)  
**Deployment:** Vercel  

---

## System Architecture

1. **Frontend (Next.js)** handles routing, UI, and serverless API routes.  
2. **Supabase** manages user data, car listings, and image storage.  
3. **Prisma ORM** simplifies database operations.  
4. **AI model** (Python) runs separately for price prediction and image-based search.  
5. **Clerk** manages secure login and access roles.  
6. **ArcJet** provides app-level security.

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Prashantasp/Vehiql.git
   cd vehiql
