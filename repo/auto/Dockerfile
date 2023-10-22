FROM ghcr.io/onlinegears/chrome:latest

RUN apt-get update && \
	DEBIAN_FORNTEND=noninteractive apt-get upgrade -y \
	&& DEBIAN_FORNTEND=noninteractive apt-get install -y \
		python3 python3-pip \
	&& pip3 install selenium selenium-wire chromedriver-binary-auto
