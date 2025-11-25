# TDE-04

# ShopNow — Load Balancer + Multiple Instances Demo


```bash
docker-compose up --build -d

http://localhost:8080/


http://localhost:8081/


docker-compose stop app2


ab -n 10000 -c 200 http://localhost:8080/


