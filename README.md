# ☁️ Nube - Modern File Management System

![Nube Banner](https://via.placeholder.com/1200x400.png?text=Nube+File+Management)

<div align="center">

[![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.0-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Appwrite](https://img.shields.io/badge/Appwrite-1.4-FD366E?style=for-the-badge&logo=appwrite)](https://appwrite.io/)

</div>

## 🚀 Overview

**Nube** is a sleek, modern file management solution designed to simplify how you store, organize, and share your digital assets. Built with performance and user experience in mind, Nube offers a robust platform for individuals and teams to manage their files securely and efficiently.

## ✨ Key Features

- **📂 Smart File Organization**: Automatically categorize files by type (Images, Documents, Media).
- **📊 Interactive Dashboard**: Visualize storage usage and recent activity at a glance.
- **🔐 Secure Authentication**: Robust user management powered by Appwrite.
- **⚡ Fast Uploads**: Optimized file transfer for files of all sizes.
- **🔍 Advanced Search**: Quickly find what you need with powerful search and filtering.
- **📱 Responsive Design**: Seamless experience across desktop, tablet, and mobile devices.

## 🛠️ Tech Stack

- **Framework**: [Next.js 14](https://nextjs.org/) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) & [Shadcn UI](https://ui.shadcn.com/)
- **Backend & Auth**: [Appwrite](https://appwrite.io/)
- **Forms**: [React Hook Form](https://react-hook-form.com/) + [Zod](https://zod.dev/)

## 🏁 Getting Started

Follow these steps to set up Nube locally on your machine.

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- An [Appwrite](https://appwrite.io/) account and project

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/nube.git
   cd nube
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Configure Environment Variables**
   Create a `.env` file in the root directory and add your Appwrite credentials:
   ```env
   NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
   NEXT_PUBLIC_APPWRITE_PROJECT="your_project_id"
   NEXT_PUBLIC_APPWRITE_DATABASE="your_database_id"
   NEXT_PUBLIC_APPWRITE_USERS_COLLECTION="your_users_collection_id"
   NEXT_PUBLIC_APPWRITE_FILES_COLLECTION="your_files_collection_id"
   NEXT_PUBLIC_APPWRITE_BUCKET="your_bucket_id"
   NEXT_APPWRITE_KEY="your_secret_key"
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to see the application running.

## 📸 Screenshots

| Dashboard | File View |
|:---:|:---:|
| ![Dashboard](https://via.placeholder.com/600x400.png?text=Dashboard+Preview) | ![File View](https://via.placeholder.com/600x400.png?text=File+View+Preview) |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
