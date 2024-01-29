# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

Pick pizza you want, make order and track progress!

Features:

add pizza to cart, choose quantity of each
track what you already have in cart
make order by complete form with phone, address (possible to use geolocation)
add order to priority queue by paying extra money
no payment processing

Tech Features:
application uses backend servise to fetch and post data (remote state)
that remote state manage by react router data loading feature ("rendre as you fetch") and router action to post data to remote api
global UI state manage be redux-toolkit, split global state on slices
styling: Tailwindcss, responsive design (mobile first)

This project is build with:
React
TypeScript
Tailwindcss
Vite

React third-party packeges:
React Router
React Redux
