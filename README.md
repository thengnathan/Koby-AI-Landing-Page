# Koby AI Landing Page

A modern, responsive landing page for Koby AI - your intelligent business automation partner.

## 🚀 Features

- **Modern Design**: Sleek, animated UI with smooth transitions and hover effects
- **Responsive Layout**: Fully responsive across all devices (desktop, tablet, mobile)
- **Interactive Components**: Animated backgrounds, floating feature carousels, and dynamic pricing cards
- **Multiple Service Pages**: 
  - AI Suites
  - AI Chatbot
  - Phone Service
- **User Journey**: Integrated checkout and meeting scheduling flow
- **SEO Optimized**: Proper meta tags and semantic HTML

## 🛠️ Technologies Used

- **Next.js 14**: React framework for production
- **TypeScript**: Type-safe JavaScript
- **Tailwind CSS**: Utility-first CSS framework
- **Framer Motion**: Animation library for React
- **Lucide React**: Beautiful icon library
- **PostCSS**: CSS processing

## 📁 Project Structure

```
Koby-Landing Page (Light)/
├── app/                      # Next.js app directory
│   ├── about/               # About page
│   ├── ai-suites/           # AI Suites service page
│   ├── articles/            # Articles blog section
│   ├── chatbot/             # AI Chatbot service page
│   ├── checkout/            # Checkout page
│   ├── contact/             # Contact page
│   ├── get-started/         # Get Started page
│   ├── phone-service/       # Phone Service page
│   ├── schedule-meeting/    # Meeting scheduler
│   ├── globals.css          # Global styles
│   ├── layout.tsx           # Root layout
│   └── page.tsx             # Home page
│
├── components/              # React components
│   ├── AnimatedBackground.tsx
│   ├── FloatingFeaturesCarousel.tsx
│   ├── Footer.tsx
│   ├── ImprovedGrowthChart.tsx
│   ├── KobyLogo.tsx
│   ├── LandingHero.tsx
│   ├── LoadingScreen.tsx
│   ├── NavBar.tsx
│   ├── NewTestimonialsSection.tsx
│   └── PricingSection.tsx
│
├── public/                  # Static assets
│   ├── logo.png
│   ├── favicon.ico
│   └── favicon-16x16.ico
│
├── DOCUMENTATION.md         # Comprehensive documentation
├── README.md                # This file
└── package.json             # Dependencies and scripts
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd "Koby-Landing Page (Light)"
```

2. Install dependencies:
```bash
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

### Build for Production

```bash
npm run build
npm start
```

## 📝 Available Pages

- **Home** (`/`) - Main landing page
- **About** (`/about`) - About Koby AI
- **AI Suites** (`/ai-suites`) - AI solution suites
- **AI Chatbot** (`/chatbot`) - Chatbot service
- **Phone Service** (`/phone-service`) - Phone automation service
- **Get Started** (`/get-started`) - Plan selection
- **Checkout** (`/checkout`) - Checkout process
- **Schedule Meeting** (`/schedule-meeting`) - Meeting scheduler
- **Contact** (`/contact`) - Contact us
- **Articles** (`/articles`) - Tech articles and insights

## 🎨 Styling

The project uses Tailwind CSS for styling. Custom colors and animations are configured in:
- `tailwind.config.js` - Tailwind configuration
- `app/globals.css` - Global styles and custom classes

### Key Features:
- Instant hover animations (150ms transitions)
- Glow effects for service icons
- Responsive grid layouts
- Gradient backgrounds
- Smooth scrolling

## 📧 Contact

- **Email**: admin@kobyai.com
- **Phone**: (559) 960-9723

## 📋 TODO

See [DOCUMENTATION.md](./DOCUMENTATION.md) for a detailed list of pending tasks including:
- Connect social media links in footer
- Implement email subscription
- Connect contact form to email service
- Integrate Google Calendar for scheduling

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is proprietary software of Koby AI.

## 🙏 Acknowledgments

- Built with [Next.js](https://nextjs.org/)
- Icons from [Lucide](https://lucide.dev/)
- Animations powered by [Framer Motion](https://www.framer.com/motion/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)
