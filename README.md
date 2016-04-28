EXPLANATION
Leaky Rivers solved the #EarthLive challenge.
Recently there has been major flooding in Houston, TX, USA. People - friends - lost their homes because they were not equipped with a sufficent warning system. The daily news has not been able to provide necessary real time and high resolution data on the rising water level around their homes. They have lost everything!
FLOODING happens anywhere on Earth.
Our unique approach is to combine Internet of Things (IoT) sensor data on water levels and satellite imagery from NASA's MODIS program with real time and geolocated messages on Twitter. Tweets are filtered on #flood. A tone analysis is performed and it rates people's sentiment.
This flowchart gives an overview of the current Leaky Rivers implementation. For rapid prototyping purposes we are using IBM Bluemix as cloud based developer platform. Different Services are deployed there:
Twitter Tone Analyzer
Weather Forecast Service
IoT Integration Platform (for RasPi and other devices)
Database System
As external resources and tools we integrated:
Open Layers as Map service
NASA MODIS EO data on floods
The product is a responsive web page that immediately gives an accurate overview of the flood threat level based on your geolocation.

