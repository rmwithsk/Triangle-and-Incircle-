## Triangle & Incircle Problem
![Triangle Diagram](Document 12_1.jpg) 

### Problem Overview
The problem involved a triangle with an incircle radius of 4 cm, where one side was divided into segments of 6 cm and 8 cm by the point of tangency of the incircle. The goal was to determine the smallest side of the triangle.

### First Attempt
My initial approach was to use congruency and perimeter-based reasoning, since the division of a side suggested a relationship between side lengths. I tried to reconstruct the triangle directly from the side information, assuming that the perimeter could be calculated easily. I first proved the triangles along the line joining
vertices and circle are congurent. 
It was progressing smooth but faltered when the third side couldn't be found. 

### Why It Failed
This approach became complicated and unclear because it did not take the incircle into account. Focusing only on side lengths ignored the key geometric information provided, and the reasoning quickly became messy.As I forgot that what they have in common is area.

### Key Insight
I realized that the incircle radius connects directly to the area and semiperimeter of trianglele through the formula:

> Area = r × s

where r is the inradius and s is the semiperimeter. The given side segments (6 cm and 8 cm) correspond to expressions involving (s − a), (s − b), and (s − c), which allowed the problem to be approached systematically.

### Final Approach
Using Heron’s formula for the area and substituting Area = r × s, I derived an expression entirely in terms of the side lengths a, b, and c. With the inradius given as 4 cm and the side split into 6 cm and 8 cm, I solved the equations to identify the smallest side.

### What I Learned
This problem taught me to first identify the central geometric object before choosing a method. Aligning my approach with the incircle simplified the solution and reinforced the importance of area-based reasoning in triangle geometry. It also showed me the value of systematically analyzing where initial attempts fail and how to correct them.
