**Canada Freight Analysis** - Analysis of Mode of Transports between different provinces 
                          in Canada between 2011 - 2017

**Findings** - 
1. Total Number of Shipments each year 
2. Most common modes of transportation
3. Commodities shipped most frequently
4. Avg weight of shipments per year
5. Total Revenue generated each year
6. Avg distance travelled by shipments each year
7. Trend between origin city and destination city - year wise
8. Statistical relation between (Distance and Shipment Value), (Shipment and Revenue), Revenue and (Shipment and WeightKg),  
   Shipment value and (Shipment,WeightKg, Distance, Revenue, TonneKm )

**Conclusion** - 
1. Ontario is the most popular Origin and Destination province in Canada. 
2. Trucks are the most common mode of transportation 
3. Food, Forest Products, Base metals and articles of base metal are the most common commodities w.r.t total shipments. 

4. Shipment vs Revenue ------
   The regression analysis suggests that there is a statistically significant positive relationship between shipments and revenue. 
   On average, an increase in   shipments is associated with an increase in revenue. 
   Correlation coefficient --- 0.64, R Square --- 0.41

5. Distance vs Shipment Value --- 
   Correlation coefficient --- 0.368, R Square Value - 0.135
   The regression analysis suggests that there is a statistically significant positive relationship between distance and shipment value. 
   On average, an increase in distance is associated with an increase in shipment value. 

6. Relation b/w Shipment value and (Shipment,WeightKg, Distance, Revenue, TonneKm )

   Correlation coefficient - 0.779, R Square value - 0.60

   Coefficients

        Intercept	11306730.1

        X Variable 1	24169.45141

        X Variable 2	-0.559483249

        X Variable 3	-11.17552351

        X Variable 4	40.89071035

        X Variable 5	-0.650916327

   X Variable 1 (Shipment): - Indicates that, on average, each additional unit of shipment is associated with an increase in shipment value of approximately $24,169.45.

   X Variable 2 (WeightKg): - suggests that, on average, each additional unit of weight (in kilograms) is associated with a decrease in shipment value by 
                              approximately $0.559.

   X Variable 3 (Distance): - suggests that, on average, each additional unit of distance is associated with a decrease in shipment value by approximately $11.18.

   X Variable 4 (Revenue):  - indicates that, on average, each additional unit of revenue is associated with an increase in shipment value of approximately $40.89.

   X Variable 5 (TonneKm):    suggests that, on average, each additional unit of TonneKm is associated with a decrease in shipment value by approximately $0.651.

   The multiple linear regression model suggests that the combination of Shipment, WeightKg, Distance, Revenue, and TonneKm  
   significantly predicts shipment value. The model explains a substantial portion (60.7%) of the variability in shipment value. 
   Each coefficient represents the estimated change in shipment value for a one-unit change in the corresponding independent variable, holding other 
   variables constant.
