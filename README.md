# dust

The project has a cascade design pattern. The first model is to predict the land surface indicators related to dust emission. The second model is to predict the dust emission based on the first model's output. 

There are two methods (convert method and ml method) in the first model.
The convert method is a physical model and ml is a data-driven model.

The second model is WEMO, which is a physical model but has the statistic optimization for some physical process, such as wind speed and vegetation pattern. 

