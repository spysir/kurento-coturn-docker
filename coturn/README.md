# coturn-docker

git clone https://github.com/spysir/kurento-coturn-docker

cd /kurento-coturn-docker/coturn/

docker build --tag yesir/coturn:4.4.5.3 .

docker run -d --restart=always --name=turnserver -p 3478:3478 -p 3478:3478/udp yesir/coturn:4.4.5.3
