# Freqtrade-Tester

If you want to update pairs [user_data/pairlists.json](user_data/pairlists.json) from `exchange:pair_whitelist` or timeframe from [docker-compose.yml](docker-compose.yml) from `download-data:timerange`, run the following after you changed.

```bash
docker-compose run --rm download-data
```