
  # Muhammad Tahir Abbas - Digital Marketing Portfolio

A modern, responsive portfolio website showcasing digital marketing expertise, built with React and TypeScript.

## Features

- **Responsive Design**: Fully responsive across all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Contact Integration**: Appwrite database integration for contact form submissions
- **Performance Optimized**: Fast loading times and optimized assets
- **SEO Friendly**: Meta tags and structured data for better search engine visibility

## Tech Stack

- **Frontend**: React 18, TypeScript
- **Styling**: Tailwind CSS
- **Build Tool**: Vite
- **Database**: Appwrite
- **Animations**: Framer Motion
- **Icons**: Lucide React
- **UI Components**: Radix UI

## Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # Base UI components
│   └── figma/          # Image components
├── pages/              # Page components
├── data/               # Project and static data
├── services/           # API and service integrations
└── styles/             # Global styles
```

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd digital-market-portfolio
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
```bash
cp .env.example .env
```

4. Configure your Appwrite credentials in `.env`:
```env
VITE_APPWRITE_ENDPOINT=your-appwrite-endpoint
VITE_APPWRITE_PROJECT_ID=your-project-id
VITE_APPWRITE_DATABASE_ID=your-database-id
VITE_APPWRITE_STORAGE_ID=your-storage-id
VITE_APPWRITE_CONTACT_COLLECTION_ID=your-contact-collection-id
```

5. Start the development server
```bash
npm run dev
```

## Database Setup

For contact form functionality, set up an Appwrite database with a contact collection. Refer to `APPWRITE_SETUP.md` for detailed instructions.

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## Contact Form

The contact form integrates with Appwrite to store submissions securely. Features include:
- Form validation
- Loading states
- Error handling
- Success notifications

## Deployment

The project is optimized for deployment on:
- Netlify
- Vercel
- GitHub Pages
- Any static hosting service

Build the project with `npm run build` and deploy the `dist` folder.

## License

This project is licensed under the MIT License.

## Contact

Muhammad Tahir Abbas - [info.thetahirabbas@gmail.com](mailto:info.thetahirabbas@gmail.com)

Project Portfolio: [View Live Site](https://tahir-portfolio.netlify.app)
  