# Ecological Monitor Challenge

The goal of this challenge is to assess your problem solving ability when presented with a geospatial problem. Change detection is a classic example of remote sensing analysis and can be used for a variety of use cases including monitoring forest disturbance, land degredation, and mapping ecosystem connectivity.

## The Challenge

This challenge consists of using multispectral satellite imagery to identify vegetation change in a forested region in Tanzania from 1993 to 2016.  In the data folder you will find two Landsat images, along with a GeoJSON defining the study area. Your task is to create a land cover classification visualizing the change between the two points in time. To keep it simple, your classification only needs to have the following four classes: 

Code / Value |  Land Cover Class       | Description
------------ | :---------------------- | :------------------------------------------------------
11           | __Forest-Forest__       | areas dominated by forest which saw no transition
12           | __Forest-NonForest__    | forested areas which transitioned to non-forested areas 
21           | __NonForest-Forest__    | non-forested areas which transitioned to forested areas
22           | __NonForest-NonForest__ | non-forested areas which saw no transition


Using whatever methods available, visualize your results for the study area. Your final result can be presented in fashion. Feel free to use any tools available (ArcGIS, QGIS, ENVI, etc...) and bonus points for programming!

## Resources

- The 
- For more information on the images being used, go to the [USGS Landsat page](https://www.usgs.gov/faqs/what-are-best-landsat-spectral-bands-use-my-research?qt-news_science_products=0#) to see what bands are included in each image
- Check out [Github](https://github.com/sacridini/Awesome-Geospatial#python) for a list of helpful of tools and open source packages you 
- Ask us questions! Shoot us an email, or talk to us on [Discord](https://discord.gg/stujhkkhvk), if you need help.

## Submission

For submission, please send us an email with a zip folder containing your project or a link to your Github repo. Please include all data, intermediary layers, written code, and results. And don't forget to add a nice README.md documenting your workflow :)

## Additional Information

### Expected Timeline

The entire task should only take 2-3 hours, but you’re free to take as long as you like. We don't expect you to come up with a perfect solution. Whenever you run out of time, add a comment describing what you would have done if you had more time.

### Documentation

With this take home task we would like to understand how you tackle tasks like the one above. In order for us to easier understand your thought process, please make sure to include a well documented README or upload a text or word document explaining each step. 

Feel free to include a list of ideas on how to improve your final project under the assumption that you have unlimited time and resources to spend on it.
