# Geospatial-Football-Analytics

**Geospatial-Football-Analytics** is a project that combines geospatial data analysis with football analytics to gain insights into player movements, passing actions, and team tactics. Using data from football matches, this project applies geospatial techniques to track, visualize, and analyze different aspects of the game, including player positioning, passing distances, and movement patterns on the pitch.

## Key Features:
- **Euclidean Distance Computation:** Calculates the Euclidean distance between origin and destination points of passes and drives to analyze the distance covered during each action.
- **Classification of Passes/Drives:** Classifies passes and drives into short, mid-range, and long categories based on distance traveled.
- **Attacking Playstyle Analysis:** Applies various functions to classify passes and drives, helping to analyze the team's attacking style based on their positional movements and actions (e.g., passes to the defending area, progressive passes, etc.).
- **Geospatial Visualization:** Utilizes the `_draw_field()` function to visualize key match features, such as passes finishing inside the defending area, progressive drives in the final third, and progressive passes into half-spaces, with customized color schemes for clear and effective data presentation.

## Technologies Used:
- Python (Pandas, NumPy, Matplotlib)
- Geospatial data analysis
- Football match tracking data

