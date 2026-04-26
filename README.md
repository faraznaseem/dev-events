# 🎟️ DevEvents – Event Management Platform

A full-stack event management platform built to create, manage, and showcase events with a dynamic user experience. The platform supports event creation, image uploads, registration flows, and event discovery with optimized performance using modern web technologies.

---

## 🚀 Features

- 📅 Create, update, and manage events with full CRUD functionality  
- 🔍 Browse and discover upcoming and featured events  
- 🖼️ Upload and manage event images using cloud storage  
- 🧾 Event detail page with registration functionality  
- 🎯 Related events suggestions based on event context  
- ⚡ Optimized performance using server-side rendering and caching strategies  
- 📱 Fully responsive UI for all device sizes  

---

## 🛠️ Tech Stack

- Next.js – Full-stack React framework  
- TypeScript – Type-safe JavaScript development  
- MongoDB – NoSQL database for flexible data storage  
- Mongoose – ODM for MongoDB schema modeling  
- Tailwind CSS – Utility-first CSS framework  
- Cloudinary – Image upload and media optimization  

---

## ⚙️ Key Implementations

### 🔹 RESTful API Design
Built scalable API routes for CRUD operations with proper validation and structured responses.

### 🔹 Image Upload & Management
Integrated Cloudinary for optimized image upload, storage, and delivery.

### 🔹 Dynamic Event Pages
Developed event detail pages with registration flow and contextual event recommendations.

### 🔹 Performance Optimization
Used Next.js caching strategies and server-side rendering to improve page load performance.

### 🔹 Scalable Data Modeling
Designed MongoDB schemas using Mongoose for efficient and flexible event data handling.

---

## 🔑 Environment Variables

Create a `.env` file in the root directory and add:

```env
NEXT_PUBLIC_BASE_URL=http://localhost:3000/

MONGODB_URI=your_mongodb_connection_string

CLOUDINARY_URL=your_cloudinary_url
```

## Installation

git clone https://github.com/your-username/dev-events.git
cd dev-events
npm install
npm run dev
