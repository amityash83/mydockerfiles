#
# Ubuntu base image, see README for more details
#
FROM ubuntu:16.04

# Add some core repos
RUN apt-get update && \
	apt-get install -y \
	sudo apt-transport-https ca-certificates curl vim zip openssl build-essential \
	software-properties-common python-software-properties iputils-ping net-tools locales && \
	apt-get clean;
