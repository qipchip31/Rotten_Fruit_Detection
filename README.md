# Rotten_Fruit_Detection

This project focuses on developing a comprehensive method for assessing fruit decay using a combination of computer vision and microwave technologies. The aim is to ensure the quality of fruits by accurately detecting both external and internal decay, thus reducing food wastage and economic losses.


## Abstract
The project aims to create a reliable and non-destructive method for fruit decay assessment by combining computer vision for external decay detection and microwave technology for internal decay assessment.

### Importance of Fruit Quality Assessment
- Ensuring fruit quality is essential in the food industry to prevent spoilage and ensure consumer satisfaction.

### Challenges in Assessing Fruit Decay
- Current methods often lack accuracy and efficiency, leading to significant economic losses and food wastage.

### Proposed Methodology
- **Two-Step Approach**: Initial external decay assessment using computer vision, followed by internal decay detection using microwave technology.

## Methodology

### Computer Vision in Fruit Assessment
- **Explanation**: Computer vision techniques are employed to detect visible external decay, such as discoloration, bruises, and blemishes.This uses a mobilenet architecture for the detection of rotten fruits. It contains a dataset of the rotten and freshfruits of apple, bannana and orange. This is used for the classification of the fruit to predict weather it is rotten or not. This computer vision part mainly aims in making the detection process faster if the fruit is detected as rooten from outside there is no requirement to test it with the microwave technology. If it is detected to be fresh then its internal state is accessed using microwave technology.
- **Software Requirements**: Python IDLE, Jupyter Notebook.

### Microwave Technology in Fruit Assessment
- **Explanation**: Microwave technology provides non-destructive internal decay detection by analyzing dielectric properties, moisture content, and texture. This is done using a Virtual network analyser(VNA). Here the internal state of the fruit is accessed using the S21 parameters with a frequency sweep of 1GHz - 10GHz. The CSV file generated using the VNA is used to visualize the plot of frequency vs Gain and it is also used in the NRW method to calculate the permitivity of the fruit. Using these two the freshness of the fruit is anlaysed.
- **Hardware Requirements**: Dielectric Probe Kit, Network Analyzer, 3-D Printed Conveyor Belt Prototype.
- **Software Requirements**: HFSS, Ansys.


### Software
- Python IDLE
- Jupyter Notebook
- HFSS
- Ansys


## Literature Survey
- **Characterization of Radio Frequency Heating of Fresh Fruits** by Sohan Birla, University of Nebraska-Lincoln.
- **Fruit and Vegetable Quality Assessment via Dielectric Sensing** by Dalia El Khaled et al.
- **Storage of Fresh Fruits and Vegetables** by Shekh Mukhtar Mansuri, ICAR-Central Arid Zone Research Institute.



