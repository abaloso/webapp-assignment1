# Responsive Navigation Menu - React App (Assignment #1)

The objective I have in mind for this project is creating my personal website wherein I can offer professional services such as Web Development and Graphic Design. The base of this project is Tailwind CSS for styling, and React Router for routing and navigation.

## Table of Contents

- [Design Choices](#design-choices)
- [Implementation Approach](#implementation-approach)
- [Functionality](#functionality)
- [Running and testing the Application Locally](#running-the-application-locally)
- [Dependencies](#dependencies)
- [Libraries and Frameworks](#libraries-and-frameworks)
- [Reference Web Apps](#inspired-web-applications)

## Design Choices

The main design choice for this application was to create a simple navbar with a quick access to the CTA for quotations. I made sure to make it as a mobile-first approach with most of the user nowadays almost always access website through their mobile devices first. Content will follow suite as I still have to think about the over layout of the website.

Key design elements:

- **Mobile-First Design**: The menu adapts fluidly to different screen sizes, with a full-width hamburger menu on small screens and a horizontal navigation bar on larger screens.
- **Smooth Transitions**: When the burger menu opens and closes, a smooth transition is used for better user interaction.
- **Clean and Minimalistic UI**: The navigation items are spaced out and minimal, with hover and focus effects for better accessibility and straightforward approach.

## Implementation Approach

As per the assignments requirements I used **React** for the component structure and **React Router** for navigation. While **Tailwind CSS** was optional, I did my best to understand it and had a crash course about it as from my research it is best for utility-first styling, responsive layout and clean, manageable code. The main feature for now is the **burger menu** that appears on smaller screens and slides into view with a smooth transition.

Here’s how the implementation works:

1. **Navigation Bar**: The `Navbar` component is responsible for rendering the main navigation. It contains my personal logom a CTA button for fast quotations and a button for the burger menu, which toggles visibility on mobile screens.
2. **Responsive Menu**: On mobile devices, the navigation items are hidden and only appear when the burger menu is clicked. On desktop devices, the menu is always visible and aligned horizontally.
3. **Routing**: The app uses **React Router** to manage the routing for different pages.

## Functionality

- **Responsive Menu**: On smaller screens, the burger menu allows users to open and close the navigation items. On larger screens, the items are displayed horizontally.
- **Smooth Transitions**: The burger menu and content transitions are animated, ensuring a seamless user experience.
- **Hover and Focus States**: Each navigation item has hover and focus states to improve accessibility.

## Running and testing the Application Locally

To run the application locally, follow these steps:

1. Clone this repository:

   ```bash
   git clone <repository-url>

   ```

2. Install Dependencies:
   cd <project-folder>
   npm install

3. Start the dev server:
   npm start

## Dependencies

**react**: The core library for building the user interface.
**react-router-dom**: Handles routing and navigation between pages.
**tailwindcss**: A utility-first CSS framework for styling.
**react-transition-group**: Handles transitions for elements during state changes. (still learning)

## Libraries and Frameworks

**React**
**React Router**
**Tailwind CSS**

## Reference Web Applications

The design of this navigation menu was inspired by different web apps that emphasize clean, user-friendly, and mobile-responsive interfaces.

**Apple’s website**: The simple, minimalistic design and smooth transitions for interactive elements like the navigation bar.
**Airbnb**: The responsive navigation system that adapts based on the screen size, providing an optimized user experience across devices.
**Netflix**: The transition animations and hover states that enhance the user experience while browsing different sections.

## Conclusion

This was my first-hand experience using React after a couple of years. My initial introduction to React was when a lead developer on one of my projects was very insistent that I learn ReactJS to help with my career path and also to create more realistic UIs for them. At the time, I wasn't sure about diving in, but it made a lot of sense as I started experimenting with React. I thoroughly enjoyed dipping my toes into it and seeing how powerful it was in building dynamic, reusable components. I'm now excited to continue improving my React skills and getting a deeper understanding of how to efficiently leverage ReactJS in my future projects. Shout-out to Tailwind CSS as well, still a long ways to go!
