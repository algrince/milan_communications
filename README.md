## Communications in Milan

This is an educational project that was made for completing Statistics in the university. The main language of the project is Spanish. The programming language is R.
This repository contains the raw code file .rmd that generates .html file that contains all the output.

### Main objectives

The main objective of the project was to elaborate a statistical report (descriptive type). The source file contained data from mobile communications in Milan from one day in 2013 (4 842 624 interactions, including incoming and outcoming SMSs, calls and web traffic).
The analysis includes these steps: 
1. Build new data sheet importing the raw data of traffic per cell. *(The map of Milan, as any other region, is divided in cells to register traffic)* The data sheet is to include:
    - The total sum of traffic for every cell
    - The average of traffic for every registered interaction
2. Add frequencies for the variable **Country code** for incoming and outcoming SMSs, calls and web traffic. Interpret the results finding countries that generate max and min of trafic for every type of interaction.
3. Add frequencies for the variable **Square id** for visualising the dymanics of generation of the interactions in Milan. 
4. Sort out data as SMS, call or Internet. Add frequencies for every type of interaction.  
5. In the same data sheet proceed to descriptive analysis of frequencies of the following variables:
    - Total traffic of incoming SMSs and its average traffic per interaction.
    - Total traffic of outcoming SMSs and its average traffic per interaction.
    - Total traffic of incoming calls and its average per interaction.
    - Total traffic of outcoming calls and its average per interaction.
    - Total traffic of Internet and its average per interaction.
6. For all the variables from the previous step, add descriptive analysis which includes measures of position, statistical dispersion and its form, identification of atypical cells.
7. Make log transformation of the same variables and repeat the same analysis with the new ones. Compare results for the normal and the log scale.  

### Optional objectives

The second part of the project is focused on graphic representation of the data. It includes downloading map of Europe (Eurostat) and of traffic grid of Milan. Additionally, Country code assigment was made.
1. Associate country codes with country (additional data).
2. Visualise variables from the main objectives in European map. For every variable add two maps: absolute frequency and relative to the population of every country (additional data, source: "World Bank Group" for 2013). Select countries with max and min traffic.
3. Visualise the raw data in the grid map of Milan. Select regions of the city with the most interactions.

### Example of the map represenation for general traffic
<details>
  <summary>General traffic</summary>
<img src="https://user-images.githubusercontent.com/98690010/199957591-b15f6e63-e21d-4294-a508-3ee89de9e5dd.png" />
</details>

<details>
  <summary>General realtive traffic</summary>
<img src="https://user-images.githubusercontent.com/98690010/199957774-d35045ee-2ea7-407a-a244-b67cf3e723f1.png" />
</details>

### Example of Milan grip map

<details>
  <summary>Full grip map</summary>
<img src="https://user-images.githubusercontent.com/98690010/199958777-76e1d53e-a7c0-40fb-8f80-441441544649.png" />
</details>

<details>
  <summary>City centre grip map</summary>
<img src="https://user-images.githubusercontent.com/98690010/199959021-85417cf1-29db-46ae-acf2-efbf367393d6.png" />
</details>
