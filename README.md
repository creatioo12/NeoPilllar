How to Play

The objective is simple: Build the tallest tower possible.

Input:

Desktop: Press Spacebar or Click to drop the moving block.

Mobile: Tap the screen to drop the block.

The Slicing Mechanic: You must align the moving block with the one below it. Any part of the block that hangs over the edge will be sliced off, making your next block smaller and harder to place.

Perfect Drops: Align a block perfectly and maintain your current block size. String together perfect drops to increase your combo and earn more coins!

Goal: Stack as high as you can. As you gain altitude, you will leave Earth, pass Mars and Jupiter, and eventually reach distant galaxies.

Key Features

Dynamic Environments: Watch the sky change from Earth Day to Sunset, then Night, Mars, Jupiter, and the Deep Galaxy as your score increases.

Block Market (Shop): Use earned coins to purchase and equip special power-up blocks (Glue, Slow-Mo, Magnet, etc.).

Loadout System: Choose exactly 3 special blocks to bring into your mission. They appear every 5th level.

Physics-Based Debris: Sliced pieces tumble away realistically based on your alignment.

High Score Tracking: Saves your altitude record and coin total locally.

Technical Specifications

Engine: Powered by Three.js using an Orthographic camera system for that classic isometric arcade feel.

Physics Logic: Features a custom-built geometry slicing algorithm that dynamically calculates overlaps and spawns debris meshes with independent velocity and rotation.

Procedural Textures: Every special block uses a custom-generated canvas texture (Zebra, Polka, Camo, etc.) to ensure a lightweight file size without external image dependencies.

Performance: Optimized for 60FPS on both mobile and desktop through efficient mesh pooling and disposal (GPU memory management).

Adaptive UI: Styled with Tailwind CSS, featuring a responsive design that shifts layouts between landscape desktop and portrait mobile views.

Audio Synthesis: Uses the Web Audio API for real-time sound synthesis, creating dynamic pitch-shifted chimes based on your current combo streak
