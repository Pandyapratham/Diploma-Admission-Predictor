# Diploma Admission Predictor 🎓

![DiplomaPredictor](https://img.shields.io/badge/DiplomaPredictor-2024-blue)
![Next.js](https://img.shields.io/badge/Next.js-14-black)
![React](https://img.shields.io/badge/React-18-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-7-green)

A sophisticated web application designed to help students predict their admission chances in diploma programs across Gujarat, India based on their academic scores, preferred branches, and categories.

## 🌟 Key Features

- **Accurate Prediction Algorithm**: 95% accurate predictions based on historical admission data
- **Comprehensive College Database**: Covers government, SFI, and grant-in-aid colleges
- **Multi-Factor Analysis**: Considers marks, category, branch preference, and location
- **Privacy-Focused**: No personal data collection, all calculations done client-side
- **Responsive Design**: Optimized for all devices from mobile to desktop
- **WhatsApp Integration**: Real-time updates through WhatsApp community
- **PDF Reports**: Generate and download your prediction results

## 📊 Supported Institutions

The predictor currently covers diploma programs in:

- **Government Engineering Colleges**
- **Self-Financed Institutes (SFI)**
- **Grant-in-Aid Colleges**
- **Polytechnics across Gujarat**

## 🛠️ Technology Stack

### Frontend
- **Framework**: Next.js 14 (App Router)
- **UI Library**: React 18
- **Styling**: Tailwind CSS with CSS animations
- **Icons**: Lucide React
- **Form Handling**: React Hook Form with Zod validation
- **State Management**: React Context API

### Backend
- **API Routes**: Next.js API endpoints
- **Database**: MongoDB Atlas
- **Authentication**: Next-Auth
- **Email Service**: Nodemailer

### Utilities
- **Data Processing**: XLSX for Excel data handling
- **PDF Generation**: jsPDF
- **Analytics**: Vercel Analytics

## 📂 Project Structure

DIPLOMA_PREDICTOR/
```
├── app/ # Next.js app directory
│ ├── (auth)/ # Authentication routes
│ ├── api/ # API routes
│ ├── contact/ # Contact page
│ ├── predict/ # Prediction tool
│ └── layout.tsx # Root layout
├── components/ # Reusable components
│ ├── auth/ # Auth components
│ ├── forms/ # Form components
│ ├── ui/ # UI elements (cards, buttons)
│ └── ... # Other components
├── config/ # Configuration files
├── constants/ # Constant values
├── context/ # React context providers
├── hooks/ # Custom hooks
├── lib/ # Utility functions
│ ├── database/ # DB connection utils
│ ├── predictors/ # Prediction algorithms
│ └── utils.ts # Helper functions
├── models/ # MongoDB models
├── public/ # Static assets
└── styles/ # Global styles 


```

## 🚀 Getting Started

### Prerequisites
- Node.js 18.x or higher
- MongoDB Atlas account
- npm or pnpm

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/DiplomaPredictor.git
   cd DiplomaPredictor
   
Install dependencies:

```
npm install
# or
pnpm install
```

Set up environment variables:
Create a .env.local file with:
```
env
MONGODB_URI=your_mongodb_connection_string
NEXTAUTH_SECRET=your_secret_key
NEXTAUTH_URL=http://localhost:3000
EMAIL_SERVER=your_email_smtp_server
EMAIL_FROM=your_email@domain.com

```
```bash
Run the development server:

npm run dev
# or
pnpm dev
Open http://localhost:3000 in your browser 
```
📱 Mobile Optimization
The application features:

Touch-friendly interfaces

Adaptive layouts for all screen sizes

Mobile-first design approach

Optimized performance for low-bandwidth connections

🔧 Configuration
Customize the predictor by modifying:

config/colleges.ts - Add/update college data

config/branches.ts - Modify available branches

config/categories.ts - Update reservation categories

🤝 Contributing
Contributions are welcome! Please follow these steps:

Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
Distributed under the MIT License. See LICENSE for more information.

📧 Contact
For inquiries or support:

* email: diplomapredictor@gmail.com
* WhatsApp: +91 7041170952


🙏 Acknowledgments

Next.js and Vercel team

MongoDB for database support

Open-source community contributors

