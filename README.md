# space-launch-api
## tech stack
```
mongodb
mongoose
express.js
node.js
axios
pm2
```
## working
```
takes data from data/kepler_data.csv 
src:https://www.nasa.gov/mission_pages/kepler/launch/index.html
gets spacex launch data from other api : https://api.spacexdata.com/v4/launches
```
## endpoints

### - v1/launches
```
we can put a get and post request foe launches
we can delete any launch by requesting a delete at /<flightnumber>
```
### - v1/planets
```
we can put a get request for planets
```

## test
```
uses jest
```
