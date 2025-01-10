# Bowel-Sonography-Analysis
Python based program for segmenting sonography videos on the bowel to create spatiotemporal and diameter mappings, along with the associated content flow.
Project Overview
This project involves analyzing videos, training a UNET model for colon wall segmentation, tracking particle movement, and plotting the generated maps. The following folders serve specific purposes within the project:
Folder Structure
•	Analysing_videos:
o	Used in VS Code or Jupyter Notebook for analyzing videos and generating different maps.
•	content_flow:
o	Responsible for tracking particles moving between the walls, whether from left to right or right to left.

Notes to Remember
•	Video File Path & ROI Settings:
o	Adjust the video file path and the Region of Interest (ROI) settings according to the specific videos being analyzed.
•	Window Size in Content Flow:
o	Modify the window size in the content flow program to match the duration of the video for accurate analysis.
o	Recommended settings:
	100 for 5-minute videos.
	200 for around 10-minute videos.
	500 for videos longer than 10 minutes.
•	Map Resizing:
o	Resize the maps to fit the desired figure dimensions. Refer to the utilities.py file located in the us_colon_experiment folder for guidance.
•	Directory Imports:
o	Update the import folder directory if necessary to align with your project structure.
