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
#### E-Commerce Integration
The Admin dashboard serves as the centralized backend for the entire e-commerce store, integrating CMS (Content Management System), administrative functionalities, and API routes.
This seamless integration ensures efficient management and smooth operation of the e-commerce platform.

#### Vendor Management
The dashboard empowers multiple vendors, automatically generating dedicated API routes for each vendor. This dynamic feature allows for comprehensive vendor control and individualized storefront management. 

#### Data Storage
Prisma, working in tandem with MySQL, serves as the backbone for storing and managing critical data, including product and store details. 
This database system allows for seamless Create, Read, Update, and Delete (CRUD) operations through the admin site, providing administrators with comprehensive control.

#### End-to-End Payment Processing
Stripe handles payment transactions, offering convenience for both administrators and customers.

#### Deployment
The frontend and backend are hosted on Vercel and are built with Next.js 13.

<br>

## Reference
References can be found on Next.js Docs. (https://nextjs.org/docs)
