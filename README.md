# Drone-technology
Content articles about drone technology 

**Creating a ortho-mosaic map
•	The 35 drone images dataset from the Bevere Island site was processed using "AGISOFT Photoscan" Drone Mapping software. 

•	Firstly, drone images were "added" to the software, and "reference setting" was done by selecting the WGS84 (4326) coordinate system. 

•	The process of creating an ortho-mosaic final drone map is "an automated process," including different tools, and it starts from "aligning images."
•	Next, "optimizing Camera Alignment" was done to correct possible distortion due to internal and external drone camera factors. 
•	The aligned and optimized drone images were run to generate a "dense point cloud model." 
•	Next, the "build mesh" tool was run to create a mesh from the dense cloud model. 
•	This mess tool was used to create "a model texture," simply clicking the build mesh tool.
•	The created build mesh is used to run the ortho-mosaic tool to create an "ortho-mosaic map." 
•	Output ortho-mosaic map's format is crucial for the next software to read the data. 
•	In this study, the ortho-mosaic map was export as the "TIFF" command from the File menu. Figure  shows the "ortho-mosaic image" of the site (accuracy: 10 m). 
