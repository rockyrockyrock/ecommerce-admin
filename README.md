# ecommerce-admin (E-Commerce Admin Dashboard)
#### This is a 2-fold project, please visit ecommerce-store GitHub page for your reference.

<br>

## Introduction
The document provides an overview of the admin dashboard and its high-level design.
This admin dashboard is designed to streamline the management of multiple vendors and stores, offering an efficient solution for e-commerce operations.
With a user-friendly interface, the admin has control over products, categories, orders, and integrated payment processing via Stripe.
My main focus will be on the store's CMS, Content Management System, and seamless auto-generated API endpoints for the store.

<br>

## Objective
- Vendor and Store Management: A central hub for users to create multiple stores.
- Content Management: Administrators can manage the store content, including products, images, categories, and billboards.
- Order Tracking: Users can manage the sales process and track the orders.
- Dashboard: Provide users insights with graphical representations of revenue and sales data.
- Authentication and Payment Processing: Implement Clerk Authentication, while Stripe integration handles secure payment processing.

<br>

## High-Level Design
#### Frontend
The user interface is built using Shadcn UI, Tailwind CSS, and React.

#### Backend
Powered by Node.js, the backend supports the business logic, data management, and API endpoints.

#### Database
Prisma in conjunction with MySQL is used for data storage. The database stores products, categories, vendors, stores, and more.

#### Payment Processing
Stripe handles payment transactions, offering convenience for both administrators and customers.

#### Deployment
The frontend and backend are hosted on Vercel and are built with Next.js 13.

<br>

## Reference
References can be found on Next.js Docs. (https://nextjs.org/docs)
