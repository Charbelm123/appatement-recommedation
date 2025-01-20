Apartment Recommendations System
Overview
This project analyzes apartment listings data to provide recommendations based on available amenities and features. The dataset test.csv contains information about apartments including amenity types and ratings.

Data Structure
The data is stored in CSV format with the following columns:

Apartment ID (UUID)
Rating (1-25)
Amenity Type
Feature Score
Available Amenities
The dataset includes various amenities such as:

Wi-Fi
Parking
Security system
Workspace
Kitchen appliances (Refrigerator, Microwave, etc.)
Bathroom facilities (Shower, Bathtub)
Entertainment (TV)
Climate control (Air conditioning, Heating)
Accessibility features
And more...
File Structure
├── AB_NYC_2019.csv
├── appartement_rec.ipynb 
├── test.csv
└── train.csv


Getting Started
Install required dependencies
Load the data from test.csv
Run the Jupyter notebook appartement_rec.ipynb to analyze recommendations
Usage
The system can be used to:

Analyze apartment amenities
Generate recommendations based on desired features
Compare apartments based on available facilities
Score properties based on amenity ratings
