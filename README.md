# ByteSpace Cyber - Nairobi's Premier Tech Hub 🚀

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Support-yellow?style=for-the-badge&logo=buy-me-a-coffee)](https://www.buymeacoffee.com/elsamm)
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-GitHub-ea4aaa?style=for-the-badge&logo=github)](https://github.com/sponsors/Samuel-Muriuki)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Site-blue?style=for-the-badge&logo=vercel)](https://bytespace-cyber.vercel.app/)

> Fast internet, expert repairs, and trusted technical support for students, freelancers, and businesses in Nairobi CBD.

## 🎬 Demo

![ByteSpace Demo](public/demo/bytespace.gif)

## 📸 Screenshots

<table>
  <tr>
    <td width="50%">
      <img src="public/screenshots/home-dark.png" alt="Homepage Dark Mode" />
      <p align="center"><strong>Homepage - Dark Mode</strong></p>
    </td>
    <td width="50%">
      <img src="public/screenshots/home-light.png" alt="Homepage Light Mode" />
      <p align="center"><strong>Homepage - Light Mode</strong></p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <img src="public/screenshots/services.png" alt="Services Page" />
      <p align="center"><strong>Services Page</strong></p>
    </td>
    <td width="50%">
      <img src="public/screenshots/pricing.png" alt="Pricing Page" />
      <p align="center"><strong>Pricing Page</strong></p>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <img src="public/screenshots/contact.png" alt="Contact Page" width="50%" />
      <p align="center"><strong>Contact Page</strong></p>
    </td>
  </tr>
</table>

## ✨ Features

- 🌐 **High-Speed Internet** - Lightning-fast fiber connection up to 100+ Mbps
- 🖨️ **Printing & Scanning** - Professional document services
- 🔧 **Device Repair** - Expert repairs for laptops, phones, and tablets
- 🛡️ **Virus Removal** - Complete malware cleanup and protection
- 🎧 **Technical Support** - Remote and on-site assistance
- 🎓 **Training & Workshops** - Learn essential computer skills
- 🏛️ **Government Services** - eCitizen, KRA, KUCCPS, NHIF, NSSF assistance
- 🎨 **Graphic Design** - Posters, flyers, logos, and more
- 📄 **Document Services** - CV writing, typing, form filling

### Additional Features

- 🛒 **Online Shop** - Computer accessories and tech products
- 📅 **Online Booking** - Book services and appointments online
- 💳 **M-Pesa Integration** - Secure payments via STK Push
- 👤 **User Dashboard** - Track bookings and orders
- 🔐 **Admin Panel** - Manage services, products, bookings, and blog
- 📝 **Blog System** - Tech tips and news with comments and likes
- 🌙 **Dark Mode** - Beautiful dark and light themes
- 📱 **Responsive Design** - Works on all devices
- 🇰🇪 **Bilingual** - English and Swahili support

## 🛠️ Tech Stack

- **Frontend**: React 18, TypeScript, Vite
- **Styling**: Tailwind CSS, shadcn/ui
- **Animations**: Framer Motion
- **Backend**: Supabase (Database, Auth, Edge Functions)
- **Payments**: M-Pesa STK Push Integration
- **State Management**: TanStack Query
- **Forms**: React Hook Form + Zod

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or bun

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Samuel-Muriuki/ByteSpaceCyber.git
cd ByteSpaceCyber
```

2. Install dependencies:
```bash
npm install
# or
bun install
```

3. Start the development server:
```bash
npm run dev
# or
bun dev
```

4. Open [http://localhost:5173](http://localhost:5173) in your browser.

## 📁 Project Structure

```
ByteSpaceCyber/
├── public/              # Static assets
│   ├── demo/           # Demo GIFs
│   └── screenshots/    # App screenshots
├── src/
│   ├── components/     # React components
│   │   ├── admin/     # Admin panel components
│   │   ├── booking/   # Booking system components
│   │   ├── dashboard/ # User dashboard components
│   │   ├── home/      # Homepage sections
│   │   ├── layout/    # Layout components
│   │   ├── shop/      # Shop components
│   │   ├── ui/        # shadcn/ui components
│   ├── contexts/      # React contexts
│   ├── hooks/         # Custom hooks
│   ├── pages/         # Page components
│   └── lib/           # Utilities
├── supabase/
│   └── functions/     # Edge functions
│       ├── mpesa-stk-push/
│       └── mpesa-callback/
└── README.md
```

## 💳 M-Pesa Integration

ByteSpace uses Safaricom's M-Pesa STK Push for secure payments:

1. User enters phone number
2. STK Push prompt sent to phone
3. User enters M-Pesa PIN
4. Payment confirmed automatically
5. Booking/order updated

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 💖 Support

If you find this project useful, please consider:

- ⭐ Starring the repository
- 🐛 Reporting bugs
- 💡 Suggesting new features
- ☕ [Buying me a coffee](https://www.buymeacoffee.com/elsamm)

## 📞 Contact

- **Location**: 123 Moi Avenue, Nairobi, Kenya
- **Phone**: +254 700 123 456
- **Email**: hello@bytespace.co.ke
- **Website**: [bytespace-cyber.vercel.app](https://bytespace-cyber.vercel.app/)

---

Made with ❤️ in Nairobi, Kenya 🇰🇪
