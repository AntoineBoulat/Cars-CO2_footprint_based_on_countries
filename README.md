
I-	Description of the designed ontology

If electric vehicles are considered by some as a revolution that will make our planet greener, others think that it is in fact more polluting than fossil fueled cars. Consequently, a lot of car buyers refuse to choose an electric car as their future vehicle, because of these biased beliefs.
Is an electric vehicle really ecological?
Indeed, the truth is: it depends. To answer the question of a car carbon footprint, we need to consider the whole lifecycle of a car: co2 emissions during production, use phase and recycling. 
On the one hand, for a thermal car like a BMW, the car manufacturer is forced to give the exact Co2 emission of his car (in g Co2/km) during its use phase. On the other hand, an electric car may not reject directly Co2 into atmosphere, but it uses electricity. And the production of electricity has a significant carbon footprint.
But electricity production differs according to countries. In France for example, the nuclear industry in France have a much lower carbon footprint than Chinese coal powered stations.

As the ecological aspect is more and more important for people, it is therefore important to create a decision support tool, based on an ontology, that will help car buyers to take a decision between an electric car and a thermal car, according to the country he lives in, and based on the studies that estimate carbon footprint during production and recycling for some cars. In addition, we take into account the price of the car, as electric vehicles tend to be more expensive than thermal ones. Thus this tool helps future consumers chose a car that falls into their budget range while minimizing its environmental impact.

We are going to classify here 4 different cars: 
-	A Tesla Model S, (Sedan electric car)
-	A Renault Zoe (urban electric car)
-	A BMW 7 Series (Sedan thermal car)
-	A Mitsubishi Mirage (urban thermal car)
And we will study their complete carbon footprint in 4 different countries:
-	France
-	Germany
-	USA
-	China
Now let us focus on the way we calculated the carbon footprint for each car, according to each country:



In an Excel spreadsheet, we first got the values of mean carbon footprint per country (in g Co2/KWh). For example, we can see that France pollutes way less than China thanks to Nuclear Energy.
For electric cars: thanks to the mean consumption per car (in KWh/Km), we can have the carbon footprint of an electric car per Km (gCo2/Km).
For thermal cars, the Carbone missions are given directly by the manufacturer.
By multiplying the carbon footprint of all the cars per Km by the range of the cars (270.000 Km here), we obtain the carbon footprint of every car during their use phase. 
Then, thanks to studies (especially from MIT), we were able to get the values of the carbon footprint of the production and recycling phases, for each of these cars.

The last column then adds all the data, computing the total carbon footprint for each car and for each country.
This carbon footprint value will be used directly in the object property of everyone.
An individual will be as such: Brand_Model_Country, and will be associated with the total carbon footprint of the car model for a given country.
You can use DL query to search for individual cars falling into different categories. For example if you search a car in the US with a medium price and average pollution, you will find the car Renault Zoe USA.
DL Query: USA and MediumPriceCar and AveragePollutingCar
Result: Renault_ZOE_Usa

Link of the protégé ontology: http://www.semanticweb.org/jerom/ontologies/2020/9/car/v2
Link of the GitHub with the protégé file, the MIRO and README.md :
https://github.com/AntoineBoulat/Cars-CO2_footprint_based_on_countries

