# Yassir ETA Prediction
My solution for the [Yassir ETA Prediction Challenge by UmojaHack Africa](https://zindi.africa/hackathons/umojahack-algeria-yassir-eta-prediction-challenge)

# The problem
Ride-hailing apps like Uber and Yassir rely on real-time data and machine learning algorithms to automate their services. Accurately predicting the estimated time of arrival (ETA) for Yassir trips will make Yassir’s services more reliable and attractive, this will have a direct and indirect impact on both customers and business partners. The solution would help the company save money and allocate more resources to other parts of the business.

The objective is to predict the estimated time of arrival at the drop-off point for a single Yassir journey.

# The data
The data contains details for 119,549 trips (train and test are split by date). Each row contains a start location and end location (reported as latitude and longitude to within approximately 100m) and the travel distance along the fastest route. Each trip also has a timestamp.

# Variables description
* ID - A unique ID
* Timestamp - Time that the trip was started
* Origin_lat, Origin_lon - Origin (in degrees latitude and longitude)
* Destination_lat, Destination_lon - Destination
* Trip_distance - Distance in meters on a driving route
* ETA - Estimated trip time in seconds

# Used libraries
* [Numpy](https://numpy.org/doc/stable/)
* [Pandas](https://pandas.pydata.org/docs/)
* [scikit-learn](https://scikit-learn.org/stable/)
* [CatBoost](https://catboost.ai/docs/concepts/about.html)
* [Matplotlib](https://matplotlib.org/contents.html)


License
----

MIT

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
