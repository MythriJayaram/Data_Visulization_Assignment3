Assignment: Force Layout Visualization Using D3.js

Requirements
1. Data Preparation
•	Source: Use the Author Network Data provided in the specified link.
•	JSON File:
o	Nodes should represent Authors.
o	Links should represent shared publications.
2. Hue channel
•	The nodes by affiliation country (top 10 countries only and the rest #A9A9A9)
3. UI
•	On mouse over, only the authors with the same affiliation should be visible, and the rest should have opacity of 0.2 (on mouse leave, should return to normal).
•	On click on each node, the data for the author should be shown (use a tooltip div, to show the author affiliation information)
4. Force Layout Visualization
•	Force Simulation:
o	Use D3.js force simulation to create a force layout visualization.
o	The size of each node should be determined by the number of degrees for node (Choose a suitable min-max scale for the domain and apply d3.scaleSqrt (r range[3, 12])).
•	Force Parameters:
o	Apply a charge using d3.forceManyBody().
o	Set the radius factor for d3.forceCollide() (use reasonable range for radius).
o	Add UI to control the parameters for forceManyBody, forceCollide and link Strength.
5. Web Page Creation
•	Visualization Web Page: Create a web page on GitHub to host the visualization.
Format the page appropriately, you can use flexbox, or bootstrap to format the visualization and UI.
Data Filtering: Exclude records that are missing:
•	Year
•	Affiliation
•	Author
Example References
•	Utilize the examples provided to guide your implementation.



Rubric for grading:

Data Preparation: Correctly use the Author Network Data to format nodes and links (20 points)
Hue Channel: Accurately color nodes by affiliation country (top 10 vs. others) (20 points)
UI Interaction: Implement hover effects and tooltips effectively (20 points)
Force Layout Visualization: Use D3.js for force simulation with appropriate node sizing (20 points)
Web Page Creation: Host a functional and well-structured web page on GitHub (20 points)
