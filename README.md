docker build -t static-site:v1 .
docker run -d -p 8080:80 --name static-site static-site:v1
