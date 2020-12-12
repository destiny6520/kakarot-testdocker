


###########################################################################################################################################################################################################################################################################################################################################################################################

FROM ubuntu:20.04

RUN cd $HOME
RUN mkdir ./app
RUN chmod 777 ./
RUN chmod +x ./
WORKDIR ./

ENV DEBIAN_FRONTEND=noninteractive
ENV TZ=Asia/Kolkata
ENV LANG en_US.UTF-8
ENV LANGUAGE en_US:en
ENV LC_ALL en_US.UTF-8

ENV PORT=21
EXPOSE 21
ENV PORT=22
EXPOSE 22
ENV PORT=3350
EXPOSE 3350
ENV PORT=3389
EXPOSE 3389
ENV PORT=7000
EXPOSE 7000
ENV PORT=7070
EXPOSE 7070
ENV PORT=8096
EXPOSE 8096
ENV PORT=9000
EXPOSE 9000
ENV PORT=9090
EXPOSE 9090
ENV PORT=32400
EXPOSE 32400
ENV PORT=32401
EXPOSE 32401

RUN apt-get install update && \
	apt-get install -y upgrade && \
	apt-get install sudo wget && \
	apt-get install update && \
	apt-get install -y curl && \
	apt-get install update && \
	curl https://rclone.org/install.sh | bash && \
	apt-get install -y git npm nmap neofetch && \
	apt-get install update && \
	apt-get install -y python3.9 python3-pip && \
	apt-get install -y docker.io && \
	pip3 install --upgrade pip && \
	apt-get install -y xrdp ubuntu-desktop && \
	apt-get install update && \
	curl -o /usr/local/bin/jq http://stedolan.github.io/jq/download/linux64/jq && \
	chmod +x /usr/local/bin/jq && \
	sudo apt-get install update && \
	sudo apt-get install --assume-yes wget && \
	sudo cd $HOME && sudo wget https://dl.google.com/linux/direct/chrome-remote-desktop_current_amd64.deb && \
	sudo dpkg --install chrome-remote-desktop_current_amd64.deb && \
	sudo apt install --assume-yes --fix-broken && \
	sudo DEBIAN_FRONTEND=noninteractive && \
    apt install --assume-yes xfce4 desktop-base && \
    sudo DEBIAN_FRONTEND=noninteractive && \
    apt install --assume-yes cinnamon-core desktop-base && \
    sudo bash -c 'echo "exec /etc/X11/Xsession /usr/bin/xfce4-session" > /etc/chrome-remote-desktop-session' && \
    sudo apt install --assume-yes xscreensaver && \
    sudo systemctl enable xrdp && systemctl start xrdp && \
    sudo ufw allow 3389/tcp && \
    sudo usermod -a -G chrome-remote-desktop $USER && \
	
	
#
#
#
























