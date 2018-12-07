```
curl -X POST \
  https://api.ecrimex.net/phish \
  -H 'Authorization: <your eCX API token key goes here>' \
  -H 'Content-Type: application/json' \
  -d '{
  "url": "http://schoolbusinessalert.space/sd/",
  "brand": "University of South Wales",
  "date_discovered": 1539429978,
  "confidence_level": 100
}'
```

```
curl --request POST \
  --url https://api.ecrimex.net/phish \
  --header 'Authorization: <your eCX API token key goes here>' \
  --header 'Content-Type: application/json' \
  --data '{"url": "http://schoolbusinessalert.space/sd/","brand": "University of South Wales","date_discovered": 1539429978,"confidence_level": 100}'
```
