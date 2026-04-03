# EduConnect - Social E-Commerce & Education Platform

A comprehensive social e-commerce platform that connects companies, educators, and users in a unified marketplace. Businesses can showcase products, educators can share knowledge, and users can discover, learn, and advertise in a vibrant digital ecosystem.

## 🌟 Platform Overview

EduConnect is a revolutionary platform that bridges the gap between commerce and education:

- **🏢 Business Hub** - Local and universal companies showcase and sell products
- **🎓 Education Center** - Educators upload videos, lessons, and educational content
- **🛍️ Social Marketplace** - Users discover products, learn, and advertise
- **💼 Advertisement System** - Paid advertising for products and services
- **🌐 Global Connection** - Connect with businesses and educators worldwide

## ✨ Platform Features

### 🏢 For Companies & Businesses
- **Product Management**: Upload, manage, and showcase products with detailed descriptions
- **Store Creation**: Build custom digital storefronts
- **Inventory Tracking**: Real-time stock management
- **Analytics Dashboard**: Track sales, views, and customer engagement
- **B2B Connections**: Partner with other businesses
- **Payment Processing**: Secure payment gateway integration

### 🎓 For Educators & Content Creators
- **Content Upload**: Share videos, documents, and interactive lessons
- **Course Creation**: Build comprehensive educational programs
- **Student Management**: Track progress and engagement
- **Monetization**: Earn from premium content and subscriptions
- **Live Sessions**: Host virtual classes and webinars
- **Resource Library**: Organize and categorize educational materials

### � For Users & Consumers
- **Product Discovery**: Browse and purchase from global businesses
- **Learning Platform**: Access educational content from expert educators
- **Social Features**: Follow, review, and interact with businesses and educators
- **Personalized Feed**: AI-powered recommendations for products and content
- **Advertisement Tools**: Promote products or services through paid campaigns
- **Shopping Cart**: Seamless checkout experience

### � Advertisement & Monetization
- **Pay-Per-Click**: Targeted advertising campaigns
- **Sponsored Content**: Promote products or educational materials
- **Ad Analytics**: Track campaign performance and ROI
- **Budget Management**: Set daily/monthly ad spend limits
- **Audience Targeting**: Reach specific demographics and interests

## 👥 User Roles & Permissions

| Platform Feature | Company | Educator | User | Admin |
|------------------|---------|----------|------|-------|
| **🏢 Business Operations** |
| Create/manage store | ✅ | ❌ | ❌ | ✅ |
| Upload products | ✅ | ❌ | ❌ | ✅ |
| Manage inventory | ✅ | ❌ | ❌ | ✅ |
| View sales analytics | ✅ | ⚠️ | ❌ | ✅ |
| Process payments | ✅ | ❌ | ❌ | ✅ |
| **🎓 Educational Content** |
| Upload videos/documents | ❌ | ✅ | ❌ | ✅ |
| Create courses | ❌ | ✅ | ❌ | ✅ |
| Manage students | ❌ | ✅ | ❌ | ✅ |
| Earn from content | ❌ | ✅ | ❌ | ✅ |
| **🛍️ Shopping & Discovery** |
| Browse products | ✅ | ✅ | ✅ | ✅ |
| Purchase items | ✅ | ✅ | ✅ | ✅ |
| Access educational content | ⚠️ | ✅ | ✅ | ✅ |
| Write reviews | ✅ | ✅ | ✅ | ✅ |
| Follow businesses/educators | ✅ | ✅ | ✅ | ✅ |
| **� Advertisement System** |
| Create ad campaigns | ✅ | ✅ | ✅ | ✅ |
| Set ad budget | ✅ | ✅ | ✅ | ✅ |
| Target audience | ✅ | ✅ | ✅ | ✅ |
| Track ad performance | ✅ | ✅ | ✅ | ✅ |
| **👤 Account Management** |
| Edit own profile | ✅ | ✅ | ✅ | ✅ |
| View analytics | ⚠️ | ⚠️ | ⚠️ | ✅ |
| Manage subscriptions | ✅ | ✅ | ✅ | ✅ |

**Legend:**
- ✅ **Full Access** - Complete functionality for this role
- ⚠️ **Limited Access** - Restricted to own content/data
- ❌ **No Access** - Feature not available for this role

**Role Definitions:**
- **🏢 Company**: Businesses selling products and services
- **🎓 Educator**: Content creators and educational providers  
- **👥 User**: Consumers and learners using the platform
- **⚙️ Admin**: Platform administrators with full system access

## 🏗️ Tech Stack

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web framework
- **MongoDB** - Database

### Frontend
- **React** - UI library
- **Redux** - State management
- **TailwindCSS** - Styling

### Mobile
- **React Native** - Cross-platform mobile development
- **Redux** - State management
- **TailwindCSS** - Styling

### Infrastructure
- **RESTful API** - Backend services
- **Docker** - Containerization
- **Documentation** - Comprehensive docs

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB
- Docker (optional)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/phanphoun/educ.git
   cd educ
   ```

2. **Install dependencies**
   ```bash
   # Backend
   cd backend && npm install
   
   # Frontend
   cd ../frontend && npm install
   
   # Mobile (optional)
   cd ../mobile && npm install
   ```

3. **Environment setup**
   ```bash
   # Copy environment templates
   cp backend/.env.example backend/.env
   cp frontend/.env.example frontend/.env
   ```

4. **Database setup**
   ```bash
   # Start MongoDB
   mongod
   ```

### Development

Start each service in separate terminals:

```bash
# Backend development server
cd backend && npm run dev

# Frontend development server
cd frontend && npm run dev

# Mobile development server
cd mobile && npm run dev

# API documentation server
cd docs && npm run dev
```

### Docker Deployment

```bash
# Start all services with Docker
docker-compose up -d
```

## 📱 Usage

1. **Create an account** or log in as a guest
2. **Set up your profile** and preferences
3. **Create your first project** or business plan
4. **Invite team members** and assign roles
5. **Track progress** with dashboards and analytics

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guide](CONTRIBUTING.md) for details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

- 📧 Email: phanphoun855.com
- 🐛 Issues: [GitHub Issues](https://github.com/phanphoun/educ/issues)
- 📖 Documentation: [Wiki](https://github.com/phanphoun/educ/wiki)

## 🙏 Acknowledgments

- All contributors who help make this project better
- The open-source community for the amazing tools and libraries
- Our users for their valuable feedback and suggestions

---

**Built with ❤️ by [phanphoun](https://github.com/phanphoun)**

![Phan Phoun](https://github.com/phanphoun.png)






