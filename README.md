# Spider web visualization in VBA 

The spider web, aka sun ray can be used to track status (using color coding) of projects in a department over a timeline (months, quarters or years as in this case). 

Each team has a designated folder with an Excel file on it, which has a defined structure. Each project can be represented by a tab in this input file. The project status is updated by the project manager. After each team (all 4 folders in this case) have been updated, the super user needs to update the main file "Spider_Web_Projects" by pressing the "Update button". All the inputs from all the tabs from the files in the folders with a number in their name will be read into the chart. 

Each project will be created using basic geometry of circle with two points, one created from the date of the update and one the angle corresponding to the project. 

![image](https://user-images.githubusercontent.com/84313162/181838466-92f23fe0-5ab8-4d2c-988a-ba3f983692f7.png)

Please note that the tool does not include any historical status tracking, only the latest status. So it can be used for status updates mainly. 
