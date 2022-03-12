# coturn-docker

git clone https://github.com/spysir/kurento-coturn-docker

cd /kurento-coturn-docker/coturn/

docker build --tag yesir/coturn .

docker run -d --restart=always --name=coturn -p 3478:3478 -p 3478:3478/udp coturn
