# 🧬 3D Natural Selection Simulator: User Guide

Welcome to the **Natural Selection Simulator**! This interactive 3D web application allows you to play "god" with a digital ecosystem. You control the rules of physics, the food supply, and the mutation rates, while the digital creatures (blobs) fight to survive, evolve, and reproduce.

This README is your instruction manual on how to navigate the website, use the controls, and trigger the AI Biologist.

---

## 🚀 1. How to Launch the Simulator

Use the website here: https://sai-teja-7.github.io/natural-selection-simulator/

---

## 🌍 2. Navigating the 3D World

The central area of your screen is the 3D terrarium where the simulation happens. 
* **Rotate Camera:** Left-click and drag anywhere on the background.
* **Zoom In/Out:** Use your mouse scroll wheel.
* **Pan Camera:** Right-click and drag.
* **Auto-Rotate:** Click the orange **"Auto Rotate: OFF/ON"** button on the bottom dashboard for a smooth, cinematic camera spin.

---

## 🎛️ 3. Using the Bottom Dashboard (Main Controls)

The horizontal bar at the bottom of the screen is your main control hub. Changes made here usually require you to restart the simulation.

* **Plate Size:** Changes the physical size of the 3D board (1x, 2x, or 3x).
* **Pop & Food:** Sets the starting number of blobs and how many green food pellets drop every morning.
* **Sim Speed:** Speeds up the physics engine. Set it to `5x` or `10x` if you want to fast-forward through generations quickly!
* **Genes (Checkboxes):** You can force certain genes to stop mutating by unchecking Speed, Size, or Sense.
* **Apply & Restart:** Click this green button whenever you change the settings above to reset the world with your new rules.
* **Pause Sim / Force End Day:** Use these to temporarily freeze time or instantly skip to the end-of-day survival calculations.

---

## ⚙️ 4. The Side Panels (Tweak the Universe)

On the left and right sides of your screen are floating glass panels. You can minimize them by clicking the `_` button in their top right corners.

### ⬅️ Left Side: Simulation Rules
Change these numbers in real-time to instantly affect the game!
* **Food to Survive / Clone:** How many pellets a blob needs to live or make a baby.
* **Carnivore Size Adv:** The percentage bigger a predator (red eyes) must be to successfully eat a prey (black eyes). Default is `1.05` (5% bigger).
* **Mutation Rate:** How wild the genetics are. A higher number means babies are drastically different from their parents.
* **Energy Economics:** Change how much energy a blob starts with, or how many calories a piece of food gives them.

### ➡️ Right Side: Math & Formulae
This panel controls the "Physics" of the world. 
* **Speed Tax:** The penalty for moving fast. Turn this up, and fast blobs will starve almost instantly.
* **Size Tax:** The penalty for being giant. Turn this up, and massive predators will burn out and die.

---

## 📊 5. Reading the Live Data

Want to prove evolution is happening? Click the orange **"Live Data Dash"** button in the top right corner. This opens three live charts:
1. **Color-Mapped Speed Distribution:** Blobs are color-coded (Purple = Slow, Teal = Average, Red = Fast). This bar chart shows you exactly how many blobs exist in each speed category. Watch the bars shift right as slow blobs get eaten!
2. **Population Over Time:** Tracks the total number of living creatures. Watch it flatline as it hits the "Carrying Capacity" of the food supply.
3. **Average Traits:** Tracks the exact numerical average of Speed and Size.

---

## 🤖 6. How to use the "AI Biologist"

In the bottom right corner, you will find the **AI Biologist** panel. This uses Google's Gemini AI to read your simulation's data and explain what is happening in simple English.

**First-Time Setup:**
1. Let the simulation run for at least 3 to 5 days so it has data to read.
2. Click the purple **"Analyze Trends"** button.
3. A browser prompt will pop up asking for your **Gemini API Key**. Paste your key and hit Enter. *(Your key is saved securely in your browser's local memory and is never shared publicly).*
4. The AI will output a short paragraph explaining the predator/prey arms race or the energy constraints currently affecting your blobs.

**The Extinction Event:**
If you make the rules too harsh and all the blobs die, the screen will turn dark and a giant **"EXTINCT"** window will appear. The AI Biologist will automatically scan the final moments of the civilization and write an "Autopsy Report" explaining why they collapsed!

