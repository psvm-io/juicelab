# juicelab:kali

# Kali Linux (Rolling)
# https://www.kali.org/
FROM kalilinux/kali-rolling:latest

# Update Kali
RUN apt update
RUN apt -y full-upgrade

# Install Kali tools
ENV DEBIAN_FRONTEND noninteractive
## Uncomment below to install tools automatically
#RUN apt -y install kali-linux-headless

# Install basic tools
RUN apt -y install nmap zaproxy nano iputils-ping

# Create data directory
RUN mkdir /root/data
