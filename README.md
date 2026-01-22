🪟 Window to the World A high-fidelity ambient immersion app.

Window to the World is a curated visual and auditory experience designed for focus, relaxation, and digital escapism. It transforms your browser into a portal, offering seamless loops of global landscapes paired with a multi-track ambient soundscape.

📸 Demo (If you record a video, you can upload it to YouTube or GitHub and put the link here!)

🚀 Features Curated Global Portals: 5 high-definition video streams including the Scottish Highlands, Oregon Forests, and Costa Rican Jungles.

Ambient Sound Engine: A custom-built audio playlist system that loops multiple tracks for a non-repetitive auditory experience.

Glassmorphism UI: A modern, minimalist interface designed to stay out of the way of the visuals.

Smart Playback: Intelligent handling of YouTube embeds and local MP4 files to bypass browser security constraints.

🛠️ The Tech Stack React.js: For state management and UI components.

Vite: For ultra-fast development and optimized builds.

HTML5 Media API: Used for controlling synchronized audio/video playback and custom mute/unmute logic.

CSS3: Featuring linear gradients and backdrop-filters for a premium feel.

🧠 The "Lessons Learned" (Developer Insights) This project was a deep dive into the complexities of modern browser security.

Bypassing ORB/CORS: Overcame ERR_BLOCKED_BY_ORB issues by strategically alternating between YouTube No-Cookie embeds and local asset hosting.

Media Interaction Policies: Implemented custom "User-Intent" sound toggles to satisfy browser autoplay requirements for audio.
