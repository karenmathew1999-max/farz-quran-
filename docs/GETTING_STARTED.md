# Getting Started with Farz Quran

Welcome to Farz Quran! This guide will help you get up and running.

## 📦 Installation

### Step 1: Prerequisites
Ensure you have the following installed:
- Git
- Node.js v14 or higher
- npm or yarn

### Step 2: Clone the Repository
```bash
git clone https://github.com/karenmathew1999-max/farz-quran-.git
cd farz-quran-
```

### Step 3: Install Dependencies
```bash
npm install
# or if using yarn
yarn install
```

### Step 4: Environment Setup
Create a `.env` file in the root directory:
```env
# Add your environment variables here
REACT_APP_API_URL=http://localhost:3001
```

### Step 5: Start Development Server
```bash
npm start
# or
yarn start
```

The application will open at `http://localhost:3000`

## 🛠️ Available Scripts

- `npm start` - Start development server
- `npm run build` - Create optimized production build
- `npm test` - Run tests
- `npm run lint` - Check code quality
- `npm run format` - Format code automatically

## 📖 Project Structure

```
src/
├── components/         # Reusable React components
├── pages/              # Page components
├── services/           # API services
├── hooks/              # Custom React hooks
├── utils/              # Utility functions
├── styles/             # Global styles
└── App.js              # Main app component
```

## 🌐 API Integration

To connect to the backend API:

1. Ensure API server is running on configured URL
2. Check environment variables
3. Review API documentation in `/docs/API.md`

## 🧪 Testing

Run tests with:
```bash
npm test
```

For coverage report:
```bash
npm test -- --coverage
```

## 🚀 Building for Production

Create an optimized production build:
```bash
npm run build
```

The build artifacts will be stored in the `build/` directory.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🆘 Troubleshooting

### Issue: `npm install` fails
- Clear npm cache: `npm cache clean --force`
- Delete `node_modules` and `package-lock.json`
- Run `npm install` again

### Issue: Port 3000 is already in use
- Kill the process using port 3000
- Or specify a different port: `PORT=3001 npm start`

### Issue: Module not found
- Ensure all dependencies are installed: `npm install`
- Check import paths are correct
- Restart dev server

## 📚 Additional Resources

- [React Documentation](https://react.dev)
- [Project Documentation](./README.md)
- [API Reference](./API.md)

## 🤝 Need Help?

- Check existing issues on GitHub
- Create a new issue with detailed description
- Reach out to maintainers

---

Happy coding! 🎉
