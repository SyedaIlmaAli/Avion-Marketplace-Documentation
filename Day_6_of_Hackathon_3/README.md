# Day 6: Marketplace Deployment and Staging Environment Setup

This README summarizes the steps and progress made on **Day 6**, focusing on preparing for deployment and setting up the staging environment for the marketplace project.

## Project Overview
The marketplace project is a modern, customer-facing application built with **Next.js**, styled using **Tailwind CSS**, and integrated with **Sanity CMS** for content management. This document details the steps involved in the deployment process, staging environment setup, and performance testing results.

## Deployment Setup

### Choosing a Hosting Platform
**Vercel** was selected as the hosting platform due to its seamless integration with Next.js projects, automatic deployment capabilities, and effective environment variable management.

- **Platform**: Vercel
- **GitHub Repository**: [GitHub Repository](https://github.com/SyedaIlmaAli/Avion--Marketplace)

### Linking GitHub Repository
The GitHub repository was successfully linked to the Vercel project for continuous integration and deployment.

### Configuring Environment Variables
The necessary environment variables were securely configured in the Vercel dashboard:

- `NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id`
- `NEXT_PUBLIC_SANITY_DATASET=production`
- `API_KEY=your_api_key`

## Deployment Process

### Step 1: Vercel Project Configuration
The GitHub repository was connected to Vercel, and the build settings for **Next.js** were configured.

### Step 2: Deploying to Staging Environment
The application was successfully deployed to the staging environment.

- **Staging URL**: [https://avion-marketplace.vercel.app/](https://avion-marketplace.vercel.app/)

### Step 3: Validating Deployment
The application was tested in the staging environment to ensure all functionalities were working as expected. It was confirmed that content was being fetched correctly from **Sanity CMS**.

### Step 4: Configuring Sanity CORS
The **CORS origin** was added to the **Sanity** dashboard to enable secure communication between **Vercel** and **Sanity CMS**. This configuration prevents cross-origin issues when fetching content from Sanity.
