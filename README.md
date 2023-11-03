# nginx_s3_minio
CLuster S3 minio with HTTP load balancer Nginx.

git clone https://github.com/byb4ik/nginx_s3_minio.git .

cfg.env_example -> cfg.env

docker-compose --env-file cfg.env up

visit ti http://127.0.0.1:9090/login  with  miniadmin / miniadmin
