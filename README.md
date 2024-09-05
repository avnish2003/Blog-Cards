This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## About project
It is a webpage consisting of variousblog cards having animation.
The cards on the webpage are created using ShadCN components.
It helps in creating the webpage beautiful and creationn easier.

## Features
Home Page (/)

Displays a list of blog cards, each showing a title and a brief description.
Fetches blog data from a mock JSON file or a simple array within the code.
Each blog card includes smooth hover animations, such as scaling up, changing shadow effects, or altering background colors.
Card Animations

Each blog card has hover animations that slightly enlarge the card (transform: scale(1.05)) and change its shadow or background color.
Smooth transitions are implemented for hover effects using transition: all 0.3s ease-in-out.
Cards have a fade-in animation when first loaded, utilizing keyframes to transition from opacity 0 to 1.
Styling with ShadCN

Utilizes ShadCN components for styling blog cards and the overall page layout.
Ensures a responsive design for both mobile and desktop screens.
Incorporates smooth transitions for buttons and links, such as background color changes when clicked.
Bonus Features (Optional)

A "View More" button for each card that smoothly expands to reveal additional content when clicked.
A "dark mode" toggle button with a smooth transition between light and dark themes using ShadCN's theming features.
A "Add blog post" button that helps user creates new blog posts asking for the necessary information in a form.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.


