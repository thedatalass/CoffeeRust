# CoffeeRust

*Quantitative Framework for Coffee Rust, Production and Futures*

__Abstract__: More than two billion cups of coffee are consumed worldwide each day. The livelihood of 120 million people depends on the coffee supply chain. Coffee rust leads to production losses of over $500 million worldwide and may affect futures prices. Coffee rust is caused by the coffee berry borer, or Hemileia vastatrix fungus, at temperatures from 10-30 C, and is one of the main diseases that attacks the coffee arábica plant. Coffee is the second largest traded commodity worldwide, with about $100 billion in volume traded annually.
  
Understanding the relationship between coffee rust, production quantities and futures prices is important to anyone affected by the coffee supply chain. This research offers a more quantitative framework for describing and visualizing the relationship between coffee rust, amount of coffee produced and futures prices.

__Data__: Original project had 337 observations for Brasil, Colombia and Papua New Guinea from 1995-1996, 2002-2005 and 2006 with five features: rain, temperature, rust, production amount and futures prices. 

__Results__: Various visualization techniques were used to establish a quantitative framework for the relationship between coffee rust, production amounts and futures prices. As rust increases, production increases. The slope for Production is 0.222 and the normalized root mean square error is 0.012. If production increases, future prices increase. The slope for Futures is 0.049 and the normalized root mean square error is 0.301. A polynomial regression shows the relationship between rust and futures being positive. The slope for Rust is 0.724 and the normalized root mean square error is 0.112.

See More at http://thedatalass.com/morning-joe-viz-project.

-------------------------------------

__November 2018 Update__ : New datasets found in 2018 changed scope of original project

__Problem__: Predict future weekly rust % amounts in Brasil using machine learning techniques with temperature, rain, production and futures variables.

__Data__ : New curated dataset has 1584 weekly Observations for Brasil from January 1, 1991-July 30, 2018. Input features are temperature, rain, production and futures. Target output is rust (by week in % of coverage on coffee plant).

__Preliminary Results__ : Multi-layer perceptron with 4 neurons and 4 layers has MSE of 56.86 (Logistic regression baseline MSE is 7155.29.)
