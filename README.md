Please take a look and build our wiki page https://github.com/lamegaton/Comm-and-Sensor---Speed-e/wiki
new line = two space 

# Power
1. library we are using: https://github.com/rocketscream/Low-Power


# Sensor
1. confidence level of car is around **5-7**
2. our max distance is 14 feet from the curve to the first white stripe line
3. on **04/18/2019**, we remove calibration code because it's not important
4. change **trig time to 20s and echo to 2s**


# Communication
1. planning to use different spreading factor for diffrent node
2. We've trying to get the downlink from TTN from node 
3. For testing and increase the range, we set the gateway to single channel and single Spreading factor (10)
4. 

## Location
1. Gateway:  
32.777651, -117.070372  

2. Node 1:   
32°46'43.9"N 117°04'23.6"W  
32.778863, -117.073228 (end segment -- sensor position)  
32.778916, -117.074302 (start segment)  

[-117.073230,32.778938]
[ -117.074297,32.778976]	
[ -117.073812,32.778647]	center 


## User interface
https://developers.google.com/maps/documentation/javascript/overlays?csw=1#ImageMapTypes
https://developer.tomtom.com/maps-sdk-web/functional-examples#traffic-flow-segments  
https://docs.mapbox.com/mapbox-gl-js/api/#customlayerinterface  
  
what we want to achieve at this point is showing **red** segment when **car <= 6**
and showing **green** segment when **car > 24** (look at matlab file to see our logic)
We can use this instead:  
https://developer.tomtom.com/maps-sdk-web/functional-examples#map-vector-geojson  
or another option: mapbox  
also we need to fetch data to mapbox...  
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Fetching_data


## Notes for team:
1. Please write code in block or function so we can easily intergrate
2. we have only 18 days left babes!
3. If you want to upload a new code with lmic, you have to change NWKey and APPKey

# Our team member:  
1. Mahrlo Amposta (power)
2. Ernesto Rodriguez  (presentation)
3. Christian Rizzo (antenna)
4. Adam Cruz (sensor, housing)
5. Mark Ewest (user interface)
6. Mayra Pulido  (user interface)
7. Son Pham (sensor, communication)
