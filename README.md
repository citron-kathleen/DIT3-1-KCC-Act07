1. What did you learn about using fragments and navigation components?
- I learned that using Fragments makes the UI more modular and reusable across different screens. Navigation Components simplified the process of switching between these fragments by managing the back stack and centralizing the navigation logic in a single graph file.

2. How did you make your UI adaptive to screen size or orientation?
- I made the UI adaptive by creating separate layout files for portrait and landscape modes using resource qualifiers. Specifically, I used a Bottom Navigation Bar for portrait mode and a Navigation Rail for landscape mode to better utilize the horizontal screen space.

3. What challenges did you face when combining Bottom Navigation and Tabs?
- The main challenge was ensuring that the Navigation Controller stayed in sync with different UI components like the Bottom Navigation and Navigation Rail during orientation changes.
I also had to handle potential crashes by using safe calls in the code to check which navigation view was currently present in the layout.
