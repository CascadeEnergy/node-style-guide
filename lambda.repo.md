##Lambda Repo Structure

####The following describes the directory structure for the `lambda` repo:

```
lambda
   |
   |_ system
         |
         |_ eventA
         |     |
         |     |_ actionA
         |     |     |
         |     |     |_ lib
         |     |     |_ support
         |     |     |    |
         |     |     |    |_ install
         |     |     |    |_ samples
         |     |     |         |
         |     |     |         |_ sampleEventA
         |     |     | 
         |     |     |_ index.js  --> exports.`actionA` = ...
         |     |     
         |     |_ actionB
         |
         |_ eventB
               |
               |_ actionA
               |_ actionB
```

####Example:
```
lambda
   |
   |_ weather
         |
         |_ dailyDataRequested
               |
               |_ getForecastIoData
                     |
                     |_ lib
                     |_ support
                     |_ index.js  --> exports.getForecastIoData = ...
```

