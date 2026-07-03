# Koyoto-Warriors
Koyoto-Warriors Project Overview : A koyoto Warriors is a 2D fighting game for two players side by side. It is developed by using plain html5 canvas , css and venilla javaScript . In the game players can move around , jump and fight with there swords. the game will begin with timer count players health will be displayed.

As someone who has played countless 2D and 3D games over the years, I have always harbored a deep passion for gaming. More than just playing them, I always had a dream to understand how they work behind the scenes and to build one myself.

Participating in this hackathon gave me the perfect opportunity to turn that curiosity into action. By taking what I learned from game development tutorials, breaking down the mechanics piece by piece, and building this project, I have finally taken my first step from being a game player to a game creator. This project represents the beginning of my journey into software engineering and interactive development.

** working :
An interactive, fast-paced 2D arcade fighting game built for two players to battle head-to-head on a single screen. This project was developed as a competitive entry for an online hackathon, focusing on smooth physics, responsive input handling, and dynamic asset rendering.

** how i built it

>>Local Multiplayer Action: Side-by-side, competitive local gameplay with unique control mapping for both players.
>>Dynamic Canvas Rendering: Built completely using HTML5 Canvas for real-time frame updating and smooth gameplay performance.
>>Physics-Based Movement: Implements custom collision boxes, jumping arcs, velocity vectors, and gravity mechanics.
>>Sprite Animation System: Animated character sheets that dynamically cycle through idle, running, jumping, and attack states depending on user input.
>>Audio Integration: Dedicated background music (BGM) framework built with the HTML5 Audio API, configured to loop seamlessly following modern browser autoplay interaction policies.
>>Language: Vanilla JavaScript (ES6+)
>>Graphics API: HTML5 Canvas Context (2D)
>>Structure: Object-Oriented Programming (OOP) using separate modular classes for the game loop, character handling, and sprite rendering.
>>Styling & Layout: Plain HTML5 and CSS3 for custom health bar tracking layouts and container positioning

** Challenges I ran into
Every project comes with its hurdles, and as a first-time game developer, this project pushed me out of my comfort zone. Here are the biggest challenges I faced and overcame:

The Complexity of Game Loops & Real-Time Collision Logic: Managing a constant animation loop while simultaneously calculating precise, real-time collision boundaries for two active players was incredibly difficult to wrap my head around initially. Ensuring the code continuously checked for weapon intersections without lagging the game took a lot of trial and error.

Making Characters "Look Alive" with Sprites: Synchronizing the character's movement physics (velocity, gravity, jumping) with the correct frame transitions in the sprite sheets was highly challenging. Getting the animation to smoothly switch from idle to a run or an attack frame without stuttering required a deep understanding of animation timing.

Grasping Object-Oriented Programming (OOP) Classes: Since I hadn't built a game architecture before, understanding how to properly use JavaScript classes and loops to manage separate game objects took a significant amount of time. Learning how to pass data between the player logic and the background rendering framework was a major learning curve.

The Final BGM Playback Puzzle: One of my biggest roadblocks happened right at the end with the background music. I spent a lot of time trying to figure out why the audio wouldn't play on launch. Through rigorous debugging, I learned about the browser’s strict sandbox autoplay restrictions and successfully fixed the event listeners so the music initializes seamlessly on the player's very first interaction.

** MY Accomplishments 
Architecture & Mechanics: The core game loop configuration and 2D physics system were built by learning from and following educational game development tutorials on YouTube.

Customizations & Debugging: Visual updates, background atmosphere tailoring, audio implementation, structure refactoring, and code debugging were entirely handled and customized by me.

** I learned
Building this game pushed me to understand foundational game development concepts from scratch:

*Object-Oriented Programming: Structuring complex logic by building isolated, reusable Sprite and Player blueprint classes.

*The Game Loop: Implementing a constant rendering loop to handle player updates, background redraws, and attack detection at consistent frame rates.

*Collision Logic: Writing explicit boundary calculations to detect when a player's attack hitbox intersects with the opponent's hurtbox.

*Browser Sandbox Restrictions: Navigating and debugging the browser's security restrictions regarding programmatic audio playback.

** Upcoming upgrads
Now that the core game engine and local multiplayer mechanics are functional, I plan to continue developing this project by adding the following features:

Character Selection & Unique Abilities: Introduce a character selection screen where players can choose different warriors, each with their own unique health pools, speed stats, and special attack moves.

AI Opponent (Single-Player Mode): Develop a basic state-machine artificial intelligence (AI) so a player can compete against the computer when a second player isn't available.

More Arenas & Dynamic Backgrounds: Design multiple stages with varying themes, environmental hazards, and parallax scrolling layers to make the battlefield feel alive.

Sound Effects Integration: Expand the audio framework to include directional sound effects for sword slashes, character grunts, jumping, and taking damage.

Health Pickups & Power-ups: Spawn random items across the canvas during a match to let players heal or temporarily boost their damage output.
