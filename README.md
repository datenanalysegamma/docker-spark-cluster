// Das Build Script ausführen

chmod +x build-images.sh
./build-images.sh

// Docker Compose starten

docker-compose up --scale spark-worker=3
