# shadowsocks-sslocal-docker

docker run -e SERVER=[Your Server] -e PORT=[Your port] -e PASSWORD='Your password' -d -p 1080:1080 -p 1080:1080/udp --restart always shadowsocks-sslocal
