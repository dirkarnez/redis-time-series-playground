redis-time-series-playground
============================
- [Time series | Docs](https://redis.io/docs/latest/develop/data-types/timeseries/#create-a-time-series)
- [RedisTimeSeries/RedisTimeSeries: Time Series data structure for Redis](https://github.com/RedisTimeSeries/RedisTimeSeries/)
- [Time series | Docs](https://redis.io/docs/latest/develop/data-types/timeseries/)
- [RedisTimeSeries | A NoSQL Time Series Database](https://redis.io/timeseries/)

### `redis-cli`
- Create a time series `TS.CREATE thermometer:1`
- Set when time = 1, value = 10.8 `TS.ADD thermometer:1  1 10.8`
- Set when time = 2, value = 20.8 `TS.ADD thermometer:1  2 20.8`
- Query all the data points `TS.GET thermometer:1`
### Using
- [dirkarnez/redis-action](https://github.com/dirkarnez/redis-action)
