# TIDES - Nuit de l'Info 2023

Welcome to TIDES, a web application built overnight during the "Nuit de l'Info" 2023 hackathon.

## The Context: Nuit de l'Info
The "Nuit de l'Info" is an annual French hackathon where student teams are challenged to build a web application from scratch in a single night, working continuously from sunset to sunrise (approximately 15 hours). It is an intense test of rapid prototyping, teamwork, and technical execution under extreme time constraints.

## The Challenge
The 2023 challenge, sponsored by Réseau Action Climat, asked participants to create a playful and educational web tool to help the general public distinguish real, effective climate solutions from misleading ones (often known as "greenwashing"). The tool needed to rely on solid figures without conflating distinct environmental issues, and crucially, without shaming individuals for their personal choices.

## Our Approach & Features
To tackle this challenge, our team took a creative and interactive approach to demonstrate how confusing and deceptive online information about "green" solutions can be. Based on the codebase, here are the key features we implemented during the 15-hour window:

### 1. The Immersive Landing Page (`index.vue`)
We created a sleek, cinematic landing page featuring the title "TIDES." With a deep-sea gradient background and smooth fade-in animations driven by AOS (Animate On Scroll), this page sets a modern, professional, and calming first impression. It draws the user in, establishing a sense of trust before the educational twist.

### 2. The Greenwashing Parody Experience (`contact.vue`)
To educate users on the "smoke and mirrors" of misleading climate solutions, we designed a secondary page that intentionally breaks every rule of good UI/UX design. Using text about a supposed "MODX 70 boat of the future" as a backdrop, we created a chaotic environment full of garish neon colors, distorted rotating videos, massive useless dropdowns, and confusing buttons that serve no purpose. 

This deliberately overwhelming and frustrating user experience acts as an interactive satire. It playfully illustrates how some "green" corporate initiatives mask a lack of real substance behind flashy, deceptive, or confusing marketing. By navigating this "worst UI" experience, users learn to recognize the hallmarks of online greenwashing.

### 3. The Easter Egg Dedication (`dedicace.vue`)
Hackathons are about team spirit as much as they are about code. We included a hidden dedication page featuring an interactive modal and some lighthearted inside jokes. This reflects the camaraderie and intense, sleep-deprived collaboration that happens when a team builds a functional web app in a single night.

## Tech Stack
Our project was built using a modern, performant web stack:
* **Framework:** Nuxt 3 (Vue.js)
* **Styling:** TailwindCSS alongside custom CSS for complex keyframe animations (such as the rising ocean bubbles).
* **Animations:** GSAP and Nuxt AOS for smooth, scroll-triggered visual effects.
* **Language:** TypeScript for type safety and robust code structure.

## Project Structure
* `pages/`: Contains the main application routes (`index.vue`, `contact.vue`, `dedicace.vue`).
* `assets/`: Holds global stylesheets, including our custom background animations (`main.css`).
* `public/`: Stores static assets such as SVG illustrations, fonts, and videos.
* `server/`: Reserved for backend endpoints and API routes within the Nuxt architecture.
* `nuxt.config.ts`: Configuration for our Nuxt modules, including Tailwind and AOS integrations.

## Setup and Installation
To run this project locally, ensure you have Node.js installed, then follow these steps:

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser and navigate to `http://localhost:3000`.

To build the application for production:
```bash
npm run build
```

## Reflections
Building TIDES in 15 hours was a thrilling challenge. It required us to make rapid architectural decisions, collaborate seamlessly, and balance technical implementation with creative storytelling. We are incredibly proud of our ability to deliver a functional, thought-provoking, and playfully critical product under immense pressure.
