# juicelab:kali

# Kali Linux (Rolling)
# https://www.kali.org/
FROM kalilinux/kali-rolling:latest

# Update Kali
RUN apt update
RUN apt -y full-upgrade

# Install Kali tools
ENV DEBIAN_FRONTEND noninteractive
RUN apt -y install kali-linux-headless

# Install other tools
RUN apt -y install nano

# Create data directory
RUN mkdir /root/data
