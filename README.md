# Veckouppgift7_TestAuto

Veckouppgift 7 – GI/CD Pipelines
1. Beskriv ett CI/CD-flöde för ett tänkt projekt (till exempel en Flask-app eller
webbtjänst).

	1a. Vad händer när utvecklaren pushar kod?<br>
  Svar: Koden pushas till tex GitHub och en CI/CD pipeline, tex GitHub Actions triggas automatiskt
  
	1b. Vilka tester ska köras?<br>
  Svar: Först bör snabba unit tester köras och sedan tyngre integrationstester. 
  
	1c. När och hur byggs applikationen?<br>
  Svar: applikationen byggs efter att testerna har körts och är godkända
  
	1d. Rita flödet som en enkel bild eller lista.<br>
  Svar: Push till GitHub<br>
  [1] CI/CD triggas<br>
       ↓<br>
  [2] Enhetstester och integrationstester<br>
      ↓<br>
  [3] Om testerna går igenom så byggs applikationen<br>
      ↓<br>
  [4] Deployment till QA miljö
  
	1e. Vad skulle kunna gå fel i flödet?<br>
	Svar: tester kan misslyckas, deploy kan misslyckas pga nätverksproblem
 
	1f. Vilka tester är viktigast i just ditt flöde?<br>
  Svar: enhetstester och integrationstester
  
	1g. Hur kan testning förbättra kvaliteten?<br>
  Svar: eventuella buggar fångas tidigt i processen och blir därmed billigare att åtgärda
  Säkerställer att befintlig kod inte bryts av ny kod
  
2. Hur tror du att automatiserad testning påverkar en utvecklares vardag?<br>
	Svar: Snabb feedback av tester för utvecklaren. Mer tid för utveckling

3. Vad är en fördel och en nackdel med att ha testning inbyggd i CI/CD-flödet?<br>
	Svar: Fångar fel innan det når produktion är en fördel. Nackel kan vara att det är tidskrävande att sätta upp initialt.

4. Om du skulle införa CI/CD i ett skarpt projekt – vad skulle du börja med?<br>
	Svar: Välja verisionshanteringsverktyg och CI/CD verktyg. Sätta upp en grundläggande pipeline och bygga ut med fler tester med tiden.

5. Jag har ingen egen erfarenhet av CI/CD verktyg. 
