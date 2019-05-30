# CoffeeRust

*Your Morning Joe: A Quantitative Framework for Coffee Rust, Production and Futures* (December 2017)

__Abstract__: The livelihood of 120 million people depends on the coffee supply chain. Coffee rust leads to production losses of over $500 million worldwide and may affect futures prices. Coffee rust is caused by the coffee berry borer at temperatures from 10-30&deg;C, and is one of the main diseases that attacks the coffee plant. Coffee is the second largest traded commodity worldwide, with about $100 billion in volume traded annually. This research offers a more quantitative framework for describing and visualizing the relationship between coffee rust, amount of coffee produced and futures prices.

__Data__: Original project had 323 observations for Brasil, Colombia and New Caledonia from 1995-1996, 2002-2005 and 2006 with five features: rain, temperature, rust, production amount and futures prices. 

"new.csv" 

__Results__: Various visualization techniques were used to establish a quantitative framework for the relationship between coffee rust, production amounts and futures prices. As rust increases, production increases. The slope for Production is 10.02 and the normalized root mean square error is 0.012. If production increases, future prices increase. The slope for Futures is -0.071 and the normalized root mean square error is 0.309. A polynomial regression shows the relationship between rust and futures being positive. The slope for Temperature is -0.006 and the normalized root mean square error is 12.184.

See More at http://thedatalass.com/morning-joe-viz-project.

__Conference Submission__: Talk submission for PyCon 2019 - not accepted

-------------------------------------

__November 2018 Update__

*Predicting Coffee Rust with Artificial Neural Networks* 

Four new datasets found in 2018 changed scope of original 2017 project

__Problem__: Predict future weekly rust % amounts at the country-level in Brasil using machine learning techniques with temperature, rain, production and futures variables.

__Data__ : New curated dataset has 1578 weekly Observations (5 times original dataset) for Brasil from January 1, 1991-July 30, 2018. Input features are temperature, rain, production and futures. Target output is rust (by week in % of coverage on coffee plant).

"brasil_imputed.csv"

__Preliminary Results__ : Multi-layer perceptron with 6 neurons and 5 layers has MSE of 47.69 (Logistic regression baseline MSE is 6619.78.)

__Conference Submission__: Poster to be presented at SciPy 2019 
