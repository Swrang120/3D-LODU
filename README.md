# LODU 3D — Mobile UI Prototype

A mobile-first early prototype for the LODU 3D game concept.

## Included in this first UI pass
- Premium dark/navy + gold mobile interface
- Signup form concept: name, mobile, email, username, password confirmation, avatar choice
- Demo UID generator and profile preview
- Baby-to-elder avatar progression concept
- Lodu-style board mockup, dice-roll demo, coins and level UI
- Global lobby / room-code concept for 2–4 players
- Profile banner shop preview with INR/USD example prices

## Run
Open `index.html` in a browser, or enable GitHub Pages from the repository's `main` branch and root folder.

## Important status
This is a **front-end prototype only**, not a complete online game yet. The repo was empty at the start of this work. Signup/login are not connected to a secure backend; UIDs are generated in the browser and are not guaranteed globally unique; rooms do not connect real players; the board is a visual mockup rather than a full 3D Ludo engine; boxing/impact sounds, animation physics, online multiplayer, friends, persistent coins/levels, admin-issued banners and real payments are not implemented yet.

## Recommended next build steps
1. Add Supabase Auth + database tables and server-side UID uniqueness.
2. Implement actual 3D characters/board using Three.js or a game engine.
3. Build validated Ludo rules, 2–4-player real-time rooms, friend requests and cross-region matchmaking.
4. Add age-stage animations, cartoon impact effects and licensed/suitable sound effects.
5. Add secure payment provider integration only after server-side order verification and platform policy review.
