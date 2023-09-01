run container
docker run --name myapp_c_nodemon -p 4000:4000 --rm -v /Users/yansen/Documents/code/learning/stream/YouTube/NetNinja/docker-crash-course/api:/app -v /app/node_modules myapp:nodemon

docker-compose up
docker-compose down
