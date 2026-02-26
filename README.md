# ChicagoAirbnbProject
Firstly, retrieve public data excel tables (publicly found on 'Inside Airbnb'). Next was to join the tables within Tableau based on matching column values between each table to create multiple charts/visualizations for a full dashboard analyzing Chicago Airbnb data released on March 11th, 2025.

# Data Source 
https://insideairbnb.com/get-the-data/

(Data only has listings from end of December 2024-March 11th, 2025 due to missing data in important columns in more recent data listings)

<img width="1765" height="385" alt="image" src="https://github.com/user-attachments/assets/c7f17e56-f87f-4bc4-9db1-92d4f92a6bbf" />

The excel files analyzed are:
* calendar.gz (1,048,576 rows)
* reviews.gz (464,255 rows)
* listings.gz (8605 rows)

Initially, all 3 .gz files are separate excel sheets. Combine them into one excel sheet to upload into Tableau for joining.

# Joining
Join each table based on Inner Joins: 
* listings.id = reviews.listing_id
* listings.id = calendar.listing_id

^ Upon joining, final join is too large for Tableau so only consider reviews from 2025. This ultimately provides more up-to-date information.

<img width="583" height="152" alt="image" src="https://github.com/user-attachments/assets/c9606461-6aa5-49ba-9764-a477cf6f3e04" />


# Visualizations/Dashboard
After joining is complete, I created numerous visualizations where each one would end up together on the final analysis dashboard.

LINK: https://public.tableau.com/app/profile/christian.casilao/viz/ChicagoAirbnbProject_17715599899670/Dashboard

<img width="2059" height="1154" alt="image" src="https://github.com/user-attachments/assets/8c75c373-e126-473d-98ef-738af1dd73e2" />

