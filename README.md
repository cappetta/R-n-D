
# getting started
```
docker build -t raytest .
docker-compose up
```

curl -v http://127.0.0.1:8265/api/jobs/ -d @cat_passwd.json -H "Content-Type: application/json"
curl http://127.0.0.1:8265/api/jobs/exploited_1/logs