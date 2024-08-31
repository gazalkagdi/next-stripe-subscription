<h1 align="center">Stripe Subscription</h1>

![Demo App](/public/demo-for-readme.png)

This project utilizes Next.js 14 with TypeScript, Prisma, and MongoDB to build a feature-rich web application with Stripe integration for managing subscriptions. It includes monthly and annual subscription plans, a Stripe Billing Portal, and uses Kinde Auth for secure authentication.

url - next-stripe-subscription-five.vercel.app/

Some Features:

- ⚛️ Tech Stack: Next.js 14, TypeScript, Prisma, MongoDB, Stripe
- 🔐 Authentication with Kinde Auth
- 💸 Monthly and Annually Subscriptions with Stripe
- 💵 Building a Stripe Billing Portal
- 🔄 Stripe Event Types
- 🌗 Light/Dark Mode

Setup .env file
DATABASE_URL=<get_your_mongo_db_url>

KINDE_CLIENT_ID=
KINDE_CLIENT_SECRET=
KINDE_ISSUER_URL=
KINDE_SITE_URL=
KINDE_POST_LOGOUT_REDIRECT_URL=
KINDE_POST_LOGIN_REDIRECT_URL=

STRIPE_MONTHLY_PLAN_LINK=<get_from_stripe>
STRIPE_YEARLY_PLAN_LINK=<get_from_stripe>

STRIPE_MONTHLY_PRICE_ID=<get_from_stripe>
STRIPE_YEARLY_PRICE_ID=<get_from_stripe>

STRIPE_SECRET_KEY=<get_from_stripe>
STRIPE_WEBHOOK_SECRET=<get_from_stripe>
NEXT_PUBLIC_STRIPE_CUSTOMER_PORTAL_URL=<get_from_stripe>

````

### Install dependencies

```shell
npm install
````

### Start the app

```shell
npm run dev
```
