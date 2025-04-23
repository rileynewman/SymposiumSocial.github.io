# SymposiumSocial
 import React from "react";
import { cn } from "@/lib/utils";

export default function HomePage() {
  return (
    <div className="flex flex-col items-center justify-center min-h-screen bg-cream text-black">
      <h1 className="text-4xl md:text-6xl font-bold mb-6 text-center">
        Quercus Social Club
      </h1>
      <a href="#" className="hover:scale-105 transition-transform">
        <img
          src="/acorn.png"
          alt="Clickable Acorn"
          className="w-24 h-24 md:w-32 md:h-32 cursor-pointer"
        />
      </a>
    </div>
  );
}

// Tailwind extension in tailwind.config.js should include:
// theme: {
//   extend: {
//     colors: {
//       cream: '#fdf6e3',
//     },
//   },
// }

