This web code is a recoded and restyled from the origin of deck.gl trips example from documentation. I restyled this code just for understanding how all pices of code are working together. 
This code is based on arcGIS API which are powered from ESRI American Organisation, and the UBER map visualization framework deck.gl which is very useful in Big data. 
The dataset of trips is a JSON file which is composed from {vendor,path,timestamps} to precise animation and finally in this code we have used the TripsLayer to make this data animation. 
I have changed some preperties in the layer to make it more orchestral. 
The json input data is an set of JSON objects. Each row is described like below : 
{
  "vendor": 1,
  "path":[
    [0.00000,0.00000], 
    . . . , 
    [1.11111,1.11111]
  ]
  "timestamp":"[0000.0000,. . .,1.1111]"
}
