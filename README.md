# E-KYC Services Platform

**Version:** 1.0.0

A comprehensive digital identity verification and business services platform built with React, Vite, and modern web technologies.

## 🚀 Features

- **User Authentication & Authorization**
  - Email/Password login
  - Google OAuth integration
  - Role-based access control (User/Admin)
  - JWT token management

- **Admin Panel**
  - User management and analytics
  - Service management
  - Transaction monitoring
  - Content management (Blogs, Coupons)
  - Subscription management

- **User Dashboard**
  - Profile management with avatar uploads
  - Service subscription tracking
  - Transaction history
  - Verification services access

- **Core Services**
  - PAN verification
  - Aadhaar verification
  - Business verification
  - Identity verification
  - Document verification

## 🛠️ Tech Stack

- **Frontend:** React 19, Vite, Tailwind CSS
- **State Management:** Redux Toolkit, RTK Query
- **Authentication:** Firebase Auth
- **Image Upload:** Cloudinary
- **UI Components:** Radix UI, Lucide React
- **Deployment:** Vercel

## 📦 Installation

```bash
# Clone the repository
git clone <repository-url>

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Fill in your API keys and configuration

# Start development server
npm run dev
```

## 🔧 Environment Variables

Create a `.env` file with the following variables:

```env
# API Configuration
VITE_API_BASE_URL=https://your-api-url.com/api

# Cloudinary Configuration
VITE_CLOUDINARY_CLOUD_NAME=your_cloud_name
VITE_CLOUDINARY_API_KEY=your_api_key
VITE_CLOUDINARY_API_SECRET=your_api_secret
VITE_CLOUDINARY_UPLOAD_PRESET=your_upload_preset
```

## 🚀 Deployment

```bash
# Build for production
npm run build:prod

# Preview build
npm run preview
```

## 📝 Recent Updates (v1.0.0)

- ✅ Fixed null reference errors in admin dashboard
- ✅ Added comprehensive error boundaries
- ✅ Improved defensive programming with null checks
- ✅ Enhanced user experience with better error handling
- ✅ Added proper .gitignore configuration
- ✅ Updated to React 19 and latest dependencies

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

MIT License - see LICENSE file for details
