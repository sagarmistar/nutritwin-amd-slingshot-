# NutriTwin: Metabolic Health Assistant
**Challenge Vertical:** Food & Health App

## Approach & Logic
NutriTwin uses a "Metabolic Mirror" logic to provide contextual food recommendations. 
- **Contextual Input:** The app captures the user's current metabolic state (e.g., Stable, Energy Dip, Stressed).
- **Nutritional Analysis Engine:** A weighted algorithm scores food items based on Glycemic Index (GI), Protein content, and Fiber, relative to the user's state. 
- **Predictive UX:** Uses "Predictive Sanctuary" design principles to suggest "Mindful Movement" (like walking) when metabolic spikes are predicted.

## How it Works
1. User selects their current state.
2. The engine filters the `FOOD_DB` to calculate a compatibility score (0-100).
3. The UI highlights "Excellent" matches to simplify healthy decision-making.

## Assumptions
- High-GI foods are discouraged during "Stressed" states to prevent cortisol-driven glucose spikes.
- Post-exercise states prioritize protein density (>20g) for muscle recovery.