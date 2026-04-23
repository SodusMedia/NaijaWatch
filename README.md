# Naija - Crime Prevention & Citizen Safety Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A citizen-powered platform for crime prevention, safety awareness, and community vigilance in Nigeria. Naija empowers citizens with information about wanted criminals, convicted individuals, and provides tools for anonymous crime reporting.

![Naija Platform](https://images.unsplash.com/photo-1450101499163-c8848c66ca85?w=1200&h=600&fit=crop)

## 🚀 Features

### Core Functionality
- **🔍 Most Wanted Database** - Browse profiles of Nigeria's most wanted criminals with detailed information and reward details
- **📋 Convicted Citizens Registry** - Access public records of convicted individuals with case details and court information
- **🤖 AI Image Search** - Upload photos to search the database using AI-powered facial recognition
- **📝 Anonymous Crime Reporting** - Submit secure, anonymous crime reports to law enforcement
- **🛡️ Safety Tips** - Access community safety resources and emergency contact information

### Admin Features
- **Dashboard Management** - Manage criminal records and update case statuses
- **Exoneration Workflow** - Process and record exonerations with official documentation
- **Record Removal** - Remove individuals from most wanted lists when apprehended

## 🛠️ Tech Stack

- **Frontend:** React 18 + TypeScript
- **Styling:** Tailwind CSS + shadcn/ui components
- **State Management:** React Query (TanStack Query)
- **Routing:** React Router DOM
- **Icons:** Lucide React
- **Build Tool:** Vite 5

## 📦 Installation

### Prerequisites
- Node.js 18+ or Bun
- npm, yarn, or bun package manager

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/naija.git
   cd naija
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   bun install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   # or
   bun dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 🏗️ Building for Production

```bash
npm run build
# or
bun run build
```

The build output will be in the `dist/` directory, ready for deployment.

## 🧪 Running Tests

```bash
npm test
# or
bun test
```

## 📁 Project Structure

```
naija/
├── src/
│   ├── components/          # Reusable UI components
│   │   ├── ui/             # shadcn/ui components
│   │   ├── Navbar.tsx
│   │   ├── Footer.tsx
│   │   ├── HeroSection.tsx
│   │   ├── StatsSection.tsx
│   │   └── WantedCard.tsx
│   ├── pages/              # Route pages
│   │   ├── Index.tsx       # Homepage
│   │   ├── MostWanted.tsx
│   │   ├── Convicted.tsx
│   │   ├── Report.tsx
│   │   ├── Find.tsx        # AI Image Search
│   │   ├── SafetyTips.tsx
│   │   ├── Admin.tsx       # Admin Dashboard
│   │   └── NotFound.tsx
│   ├── data/               # Mock data and types
│   │   └── mockData.ts
│   ├── hooks/              # Custom React hooks
│   ├── lib/                # Utility functions
│   └── App.tsx             # Main app component
├── public/                 # Static assets
├── index.html
├── package.json
├── tailwind.config.ts
├── tsconfig.json
└── vite.config.ts
```

## ⚖️ Legal & Ethical Considerations

This platform is designed for **lawful use only**. Please be aware of the following:

### Data Privacy
- All uploaded images are processed securely and are **not stored** after search completion
- Crime reports are **anonymous by default** with optional contact information
- Personal data is handled in accordance with the **Nigeria Data Protection Regulation (NDPR)**

### Legal Compliance
- All criminal records are sourced from **public court records** and verified submissions
- Information displayed includes case numbers and court details for verification
- Misuse of this platform may result in legal consequences under **Nigerian cybercrime laws**

### Content Moderation
- All submissions are reviewed before publication
- False reporting is a punishable offense
- Platform reserves the right to remove content that violates guidelines

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please read our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [shadcn/ui](https://ui.shadcn.com/) for the beautiful component library
- [Tailwind CSS](https://tailwindcss.com/) for the utility-first CSS framework
- [Lucide](https://lucide.dev/) for the icon library
- Nigerian law enforcement agencies for their commitment to public safety

## 📞 Contact & Support

- **Emergency:** Call 112 (Nigeria Emergency Number)
- **Police:** 199 or visit [npf.gov.ng](https://npf.gov.ng)
- **EFCC:** [efccnigeria.org](https://efccnigeria.org)
- **Platform Issues:** Open an issue on GitHub

---

url =https://naija-watch.lovable.app/

**Built with ❤️ for a safer Nigeria**
