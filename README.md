# Comparative Study of Countries: Tableau Course End Project
## By 
## Nikhil Sharma

Step 1: Begin by launching Tableau 2022.2 (or any available version).

Step 2: On the homepage, navigate to the 'Connect' section and select 'Excel' under 'To a file'.

Step 3: Locate and connect to the 'Global Financial Development Database - Jul2018' Excel file.

Step 4: Drag and drop the tables from the 'Data July 2018' section onto the canvas area.

Step 5: Click the 'Add' button to establish a connection to the 'Insurance Sample Dataset' Excel file.


![image](https://github.com/KirkYagami/Tableau_Comparative_Study_of_Countries/assets/106730135/a40fa1ea-418e-4f98-9bad-fac97d5bcc6b)










Step 6: Head to 'Sheet one' and rename it as 'MAP'.

Step 7: To create a map visualization, drag 'Country' from the 'Insurance Sample Dataset' to the 'Detail' Mark card. Then, select 'Map' under 'Automatic'. Add 'Income' from the 'Global Financial Development Database' to the filter, choose 'Show filter' after selecting all, and finally, assign 'Income' to the 'Color' Mark card and 'Country Code' to the 'Text' Mark card.


![image](https://github.com/KirkYagami/Tableau_Comparative_Study_of_Countries/assets/106730135/07467169-d938-4cee-bc54-6ad6a879566d)










Step 8: Generate 2 Parameters for 'Select Year' and 'Select Category'.









Step 9: To create Parameters, access the 'Data' panel, click the downward key below the 'Filter' button, and select 'Create Parameter'. Choose 'Date' for the 'Year' parameter and 'String' for the 'Select Category'.

![image](https://github.com/KirkYagami/Tableau_Comparative_Study_of_Countries/assets/106730135/df6e71e6-ec38-47fd-b303-c6d9122f97e9)














Step 10: Create a Calculated Field for the 'Select Category', including 'Categorial CY' (Current Year), 'Categorial PY' (Previous Year), and 'Growth %'. To do this, navigate to the 'Analysis' Pane, select 'Calculated Field', and perform the required calculations according to the given parameters.


![image](https://github.com/KirkYagami/Tableau_Comparative_Study_of_Countries/assets/106730135/dd0bd545-4b12-44a6-b030-262d0e54ebdd)



![image](https://github.com/KirkYagami/Tableau_Comparative_Study_of_Countries/assets/106730135/f36bdbfd-5f31-4455-8588-35fd5bfa9fa6)





Step 11: Develop a KPI Calculator by creating a new sheet, naming it 'KPI Table', and inserting the 'Select Category'. Filter 'Measure Names' for 'Categorical CY', 'Categorial PY', and 'Growth'. Add 'Measure Values' to the 'Text' Mark card.




![image](https://github.com/KirkYagami/Tableau_Comparative_Study_of_Countries/assets/106730135/f917bde6-16a4-43cf-93fe-95fd1a7cd29a)






Step 12: Create two additional Calculated Fields: 'Growth Color' and 'Growth Indicator' for the growth indicator visualization.


![image](https://github.com/KirkYagami/Tableau_Comparative_Study_of_Countries/assets/106730135/f9018d9c-9a67-4952-bf90-47f8c5bac8fb)






Step 13: For the Growth Indicator Visualization, create a new sheet, rename it 'Growth Indicator', and display 'Growth Color' as Color and 'Growth Indicator' as Text.


![image](https://github.com/KirkYagami/Tableau_Comparative_Study_of_Countries/assets/106730135/eb805bb4-ec33-4b67-99a0-629c53a22309)






Step 14: To craft a Trend Chart, generate a new sheet named 'Trend Chart'. Add 'Year' to Columns and 'Select Category Measure' to Rows. Utilize 'Year' for Pages to create a Motion Chart and activate 'Show history' and 'Trails'.

![image](https://github.com/KirkYagami/Tableau_Comparative_Study_of_Countries/assets/106730135/66181a54-0d81-45a5-b558-f126ecfb8b3b)










Step 15: Assemble a Dashboard by clicking the 'Dashboard' button, setting the size to 'Automatic'. Arrange elements including 'Map', 'Web Page', 'KPI sheet', 'Growth Indicator sheet', and 'Trend Chart sheet'. Apply filters and actions as needed for comprehensive visualization.


![image](https://github.com/KirkYagami/Tableau_Comparative_Study_of_Countries/assets/106730135/f3719ef3-0e3d-410f-9dc5-86734889ae03)
















Step 16: Once the Dashboard is prepared, it is ready for a slideshow presentation.
