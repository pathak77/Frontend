# AETHER - A Modern Jewel Site -> [link](http://20.193.152.23/)

A modern React 19 application showcasing a responsive jewelry e-commerce platform with TailwindCSS styling, Redux for state management, JWT authentication, smooth animations, modals, sliders, and date formatting. For backend setup, refer to the [Backend Repository](https://github.com/pathak77/Backend) built with Java Spring Boot.

## 📸 Preview
*Coming soon! Add a screenshot or demo link to showcase AETHER's UI.*

## ✨ Features
- **JWT Authentication**: Secure user authentication using `jwt-decode@4.0.0`.
- **State Management**: Centralized state handling with `react-redux@9.2.0`.
- **Routing**: Seamless client-side navigation with `react-router-dom@7.6.3`.
- **Animations**: Smooth UI animations powered by `motion@12.23.12`.
- **Date Formatting**: Elegant date/time formatting via `moment@2.30.1`.
- **Modals & Sliders**: Interactive UI components with `react-modal`, `react-range-slider-input`, and `react-slick`.
- **Responsive UI**: Utility-first styling with `tailwindcss@3.4.17`.
- **Performance Tracking**: Monitor web performance metrics using `web-vitals@2.1.4`.

## 📦 Dependencies
- `jwt-decode@4.0.0` → Decode JWT tokens
- `moment@2.30.1` → Date and time formatting
- `motion@12.23.12` → UI animations
- `react@19.1.0` → Core React library
- `react-dom@19.1.0` → DOM rendering
- `react-modal@3.16.3` → Accessible modal components
- `react-range-slider-input@3.2.1` → Range slider UI
- `react-redux@9.2.0` → State management
- `react-router-dom@7.6.3` → Client-side routing
- `react-scripts@5.0.1` → Create React App scripts
- `react-slick@0.30.3` → Carousel component
- `tailwindcss@3.4.17` → Utility-first CSS framework
- `web-vitals@2.1.4` → Web performance metrics

## ⚙️ Setup & Configuration

### Clone the Repository
```bash
git clone https://github.com/pathak77/Frontend.git
cd aether
```

### Install Dependencies
```bash
npm install
```

`https://your-api-url.com` with the actual backend API URL and `your_jwt_secret` with your JWT secret key. Refer to the [Backend Repository](https://github.com/pathak77/Backend) for backend setup.

### Run Development Server
```bash
npm start
```
The app will be available at `http://localhost:3000`.

### Build for Production
```bash
npm run build
```
The production-ready build will be generated in the `build/` folder.

## 🛠 Project Structure
```
src/
├── assets/          # Static files (images, icons)
├── components/      # Reusable components
├── pages/           # Page-level components
├── redux/           # Redux state management (actions, reducers, store)
├── styles/          # TailwindCSS and custom CSS
├── App.js           # Main app entry point
├── index.js         # React DOM entry point
```

