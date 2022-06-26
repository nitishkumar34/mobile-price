# Mobile Price Range Prediction
Mobile phones come in all sorts of prices, features, specifications and all. Price estimation and prediction is an important part of consumer strategy. Deciding on the correct price of a product is very important for the market success of a product. A new product that has to be launched, must have the correct price so that consumers find it appropriate to buy the product.

The data contains information regarding mobile phone features, specifications etc and their price range. The various features and information can be used to predict the price range of a mobile phone.
| Feature name |Feature description  |Type|
| --- | --- | --- |
| id | ID | Numeric|
| battery_power | Total energy a battery can store in mAh   | Numeric|
|blue|	Has bluetooth or not	|Boolean|
|clock_speed	|Speed at which microprocessor executes instructions|	Numeric|
|dual_sim|	Has dual sim support or not	|Boolean|
|fc	|Front Camera mega pixels	|Numeric|
|four_g	|Has 4G or not|Boolean|
|int_memory|	Internal Memory in Gigabytes	|Numeric|
|m_dep	Mobile Depth in cm	|Numeric|
|mobile_wt|	Weight of mobile phone	|Numeric|
|n_cores|	Number of cores of processor	|Numeric|
|pc|	Primary Camera mega pixels	Numeric
|px_height|	Pixel Resolution Height	|Numeric|
|px_width|	Pixel Resolution Width	|Numeric|
|ram	|Random Access Memory in Megabytes|	Numeric|
|sc_h	|Screen Height of mobile in cm	|Numeric|
|sc_w	|Screen Width of mobile in cm	|Numeric|
|talk_time|	Longest time that battery will last by a call|	Numeric|
|three_g|	Has 3G or not	|Boolean|
|touch_screen	|Has touch screen or not|	Boolean|
|wifi|	Has wifi or not	|Numeric|
# Accuracy of different algorithms
| Algorithm |Accuracy |
| --- | --- |
| LogisticRegression| 95% |
| Random Forest| 88% |
| LGBM | 87% |
|Decision Tree |83%|
