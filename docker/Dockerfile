FROM debian
RUN apt update
RUN apt upgrade -y
RUN apt install inetutils-ping -y
CMD ping -c3 127.0.0.1
