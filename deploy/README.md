### To build
docker build --rm -t phummelen/hero-docs:latest -f deploy/build/dockerfile .

### To run manualy
docker run --rm -it -p 80:80 phummelen/hero-docs:latest

### To run via script
It's obvious to have the start and stop script.<br />
The other scripts are there for special purposes.<br />
<br />
`sh start.sh` to start
`sh stop.sh` to stop
