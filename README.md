# FlowAutomate

Automation platform for workflow management.

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn package manager
- Git

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/sashadencookie/FlowAutomate.git
cd FlowAutomate
```

2. **Install dependencies**

```bash
npm install
```

3. **Create environment configuration**

Create a `.env.local` file in the root directory:

```env
# Add your environment variables here
```

### Development

**Start the development server:**

```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Building for Production

```bash
npm run build
```

The optimized build output will be generated in the `dist` folder.

### Preview Production Build

```bash
npm run preview
```

### Linting

**Run ESLint:**

```bash
npm run lint
```

**Fix linting issues automatically:**

```bash
npm run lint:fix
```

### Type Checking

```bash
npm run typecheck
```

## Project Structure

```
FlowAutomate/
├── src/
│   ├── components/     # Reusable React components
│   ├── pages/          # Page components
│   ├── api/            # API integration logic
│   ├── hooks/          # Custom React hooks
│   ├── lib/            # Utility functions and libraries
│   ├── utils/          # Helper functions
│   ├── App.jsx         # Main application component
│   ├── main.jsx        # Application entry point
│   └── index.css       # Global styles
├── index.html          # HTML entry point
├── vite.config.js      # Vite configuration
├── tailwind.config.js  # Tailwind CSS configuration
├── postcss.config.js   # PostCSS configuration
├── jsconfig.json       # JavaScript configuration
├── eslint.config.js    # ESLint configuration
└── package.json        # Project dependencies and scripts
```

## Technologies Used

- **React** - UI library
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **Radix UI** - Headless UI component library
- **React Router** - Client-side routing
- **React Query** - Data fetching and state management
- **React Hook Form** - Form management
- **Zod** - TypeScript-first schema validation
- **Framer Motion** - Animation library

## Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint |
| `npm run lint:fix` | Fix linting issues automatically |
| `npm run typecheck` | Run TypeScript type checking |

## Contributing

1. Create a new branch for your feature: `git checkout -b feature/your-feature-name`
2. Make your changes
3. Commit your changes: `git commit -m 'Add your feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Submit a pull request

## License

This project is private and owned by the repository owner.

## Support

For issues and questions, please open a GitHub issue in the repository.
