Final Report Summary 

While working on this LiDAR assignment, I learned how to load .laz point cloud data using Python. At first, I didn’t even know what LiDAR is or how point clouds work, but slowly I understood that these are just millions of tiny points in 3D space that show trees, ground and height differences. I also learned how to show them in 2D (top view) and 3D with colors based on height so we can understand the forest area better.

I did segmentation using ground vs non-ground and also small vs tall vegetation. I decided the height limit myself by checking the values in Z (elevation). It helped me understand that ground is lower and trees are higher. Visualization helped me see the forest structure more clearly.

For elevation modeling, I created a DEM and contour map using the grid method from the Z values. It showed that the land is not flat and has some height changes.

🔍 Key Findings

Trees are very tall in the area (high Z values)

Ground occupies a smaller portion of points than vegetation

From top-down view, forest density is visible clearly

Elevation difference helps to identify terrain patterns

⚠ Challenges Faced

Huge dataset, so plotting entire points was slow for my laptop

Understanding LiDAR formats (.laz) was little confusing at first

Segmentation logic was difficult since I didn’t know exact height ranges

🏗 Data Quality Observations

Noise points exist a little (some unexpected heights)

Classification field was mostly zeros, so I used a height-based method

Some vegetation points were extremely high (maybe tree tops or artifacts)

🌍 Real-World Use of LiDAR Visualization

Helpful in forest height monitoring and biomass estimation

Can detect landform for mapping and planning

Useful for flood modelling by identifying low areas

Helps analyze natural environment changes over time

✔ My Personal Learning

I honestly started with zero knowledge, but now I can:

Read LiDAR data

Visualize it in 2D and 3D

Separate different kinds of points

Create elevation-based maps

This assignment helped me understand LiDAR in a beginner-friendly way, and I feel more confident now.
