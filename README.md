# SEES GeoJSON Getter

This is a simple Jupyter notebook that allows you to get GeoJSON data from the [GLOBE API](https://api.globe.gov/search/swagger-ui.html#/) and upload it to ArcGIS.

# Requirements

You need to download [Jupyter](https://jupyter.org/install) and have it running in order to access and run this notebook.

You also need to download this repository onto your computer.

# Usage
To start, you must fill out the information on the first cell.

This includes the following information:  
- The start and end dates (in YYYY-MM-DD format)  
- Your User ID (found on GLOBE Observer App)  
- The protocol (either "land\_covers" or "mosquito\_habitat_mapper")

![sample photo](https://github.com/Piphi5/SEES-GeoJSON-Convert/blob/master/images/input.png)  
 
Then run the cell.

Now run the cell below that one and it should create an output file.
The output file will have this following format: "PROTOCOL-USERID\_measuredAt.json".

![sample directory](https://github.com/Piphi5/SEES-GeoJSON-Convert/blob/master/images/file.png)  

Make sure you know its location to facilitate uploading it to ArcGIS Online.

Get on an ArcGIS Online map and add a layer. Then select from _Add Layer From File_, press _Choose File_, and then find the json file that was generated.

After this step, you can configure the layer settings to your preferences and your GeoJSON should be added into AGO (_don't forget to save!_).

# Demo Video
[![](http://img.youtube.com/vi/rDMzwibFi6I/0.jpg)](https://youtu.be/rDMzwibFi6I 
)





