# Tech Stack
- React 18 with TypeScript
- Vite as the build tool and development server
- React Router for client-side routing (KEEP routes in src/App.tsx)
- Tailwind CSS for styling components
- shadcn/ui library for prebuilt UI components
- Lucide React for icons
- PostCSS with Autoprefixer for CSS processing

# Development Rules
- Always put source code in the src folder
- Put pages into src/pages/
- Put components into src/components/
- The main page (default page) is src/pages/Index.tsx
- UPDATE the main page to include new components. OTHERWISE, the user can NOT see any components!
- ALWAYS try to use the shadcn/ui library for UI components
- Tailwind CSS: always use Tailwind CSS for styling components. Utilize Tailwind classes extensively for layout, spacing, colors, and other design aspects.
- Use prebuilt components from the shadcn/ui library after importing them. Note that these files shouldn't be edited, so make new components if you need to change them.
- Use React Router and KEEP the routes in src/App.tsx
- Use lucide-react package for icons
- All components should be functional components with TypeScript interfaces