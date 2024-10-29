# E-commerce Platform

A modern e-commerce platform built with Payload CMS, Next.js, and TypeScript. This project provides a robust foundation for building scalable e-commerce applications with advanced features including:

## Features

- 🛍️ Fully featured e-commerce functionality
- 📱 Responsive design with Next.js
- 📝 Content management with Payload CMS
- 💳 Stripe integration for payments
- 🚀 TypeScript for type safety
- 🔄 Real-time updates and webhooks
- 🔐 Secure authentication and authorization
- 📊 SEO optimization
- 📦 Docker support for easy deployment

## Tech Stack

- **Framework**: Next.js
- **CMS**: Payload CMS
- **Database**: MongoDB
- **Authentication**: Custom with Payload CMS
- **Payments**: Stripe
- **Language**: TypeScript
- **Styling**: CSS Modules

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   yarn install
   ```
3. Copy the environment file:
   ```bash
   cp .env.example .env
   ```
4. Start the development server:
   ```bash
   yarn dev
   ```

The application will be available at `http://localhost:3000`

## Project Structure

- `/src` - Source code
- `/public` - Static assets
- `/src/payload` - Payload CMS configuration
- `/src/server` - Server-side code
- `/src/pages` - Next.js pages

## Development

- Run development server: `yarn dev`
- Run Stripe webhook listener: `yarn stripe:webhooks`
- Seed database: `yarn seed`
- Build for production: `yarn build`
- Start production server: `yarn serve`

## Deployment

The project is containerized with Docker. To deploy:

1. Build Docker image:
   ```bash
   docker build -t your-image-name .
   ```
2. Run with Docker Compose:
   ```bash
   docker-compose up -d
   ```
