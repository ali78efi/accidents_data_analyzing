Analyzing **Road Accidents Data -2022 **.
This project is about to analysing a dataset using pandas for exploring the dataset and also matplotlib and seabron to plot it.

**About Dataset**
"Road Accidents Dataset":

Description:
This comprehensive dataset provides detailed information on road accidents reported over multiple years. The dataset encompasses various attributes related to accident status, vehicle and casualty references, demographics, and severity of casualties. It includes essential factors such as pedestrian details, casualty types, road maintenance worker involvement, and the Index of Multiple Deprivation (IMD) decile for casualties' home areas.

Columns:

•  Status: The status of the accident (e.g., reported, under investigation).
•  Accident_Index: A unique identifier for each reported accident.
•  Accident_Year: The year in which the accident occurred.
•  Accident_Reference: A reference number associated with the accident.
•  Vehicle_Reference: A reference number for the involved vehicle in the accident.
•  Casualty_Reference: A reference number for the casualty involved in the accident.
•  Casualty_Class: Indicates the class of the casualty (e.g., driver, passenger, pedestrian).
•  Sex_of_Casualty: The gender of the casualty (male or female).
•  Age_of_Casualty: The age of the casualty.
•  Age_Band_of_Casualty: Age group to which the casualty belongs (e.g., 0-5, 6-10, 11-15).
•  Casualty_Severity: The severity of the casualty's injuries (e.g., fatal, serious, slight).
•  Pedestrian_Location: The location of the pedestrian at the time of the accident.
•  Pedestrian_Movement: The movement of the pedestrian during the accident.
•  Car_Passenger: Indicates whether the casualty was a car passenger at the time of the accident (yes or no).
•  Bus_or_Coach_Passenger: Indicates whether the casualty was a bus or coach passenger (yes or no).
•  Pedestrian_Road_Maintenance_Worker: Indicates whether the casualty was a road maintenance worker (yes or no).
•  Casualty_Type: The type of casualty (e.g., driver/rider, passenger, pedestrian).
•  Casualty_Home_Area_Type: The type of area in which the casualty resides (e.g., urban, rural).
•  Casualty_IMD_Decile: The IMD decile of the area where the casualty resides (a measure of deprivation).
•  LSOA_of_Casualty: The Lower Layer Super Output Area (LSOA) associated with the casualty's location.

You can find more in https://www.kaggle.com/datasets/juhibhojani/road-accidents-data-2022?resource=download

The project starts with loading the dataset and first look on it.
After that we have EDA section that we discover some basic knowledge about the instances and columns values.
After tha we using more plot to discover more informations from the dataset.


Usage:
1.  navigate to the project direcory.
2.  install requirements.
    > pip install -r requirements.tst
3.  open accident_analys.ipynb with a notebook like jypyter-notebook
    > python -m notebook
