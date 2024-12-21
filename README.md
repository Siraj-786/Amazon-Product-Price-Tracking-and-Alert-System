# Price Tracker

![Price Tracker Dashboard](https://images.unsplash.com/photo-1611974789855-9c2a0a7236a3?auto=format&fit=crop&q=80&w=2940)

A modern web application for tracking product prices and receiving alerts when prices drop to your target amount.

## Features

- 📊 Real-time price tracking with visual charts
- 🔔 Customizable price alerts
- 📱 Responsive design for all devices
- 📈 Historical price data visualization
- 🔗 Direct links to product pages

## Tech Stack

- **Frontend Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Build Tool**: Vite
- **Type Checking**: TypeScript
- **Linting**: ESLint

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

## Project Structure

```
src/
├── components/         # Reusable UI components
│   ├── PriceChart.tsx # Price history visualization
│   └── ProductCard.tsx # Product display card
├── types/             # TypeScript type definitions
├── App.tsx            # Main application component
└── main.tsx          # Application entry point
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## License

MIT License - feel free to use this project for your own purposes.