FROM debian:latest

RUN apt-get update &&  \
    apt-get -y install libncurses5-dev git ca-certificates binutils make gcc --no-install-recommends && \
    rm -rf /var/lib/apt/lists/*

RUN git clone https://github.com/tiehuis/2048-cli.git
RUN cd 2048-cli && make && ls -lah && cp 2048 /usr/local/bin/2048
RUN chmod +x /usr/local/bin/2048


CMD 2048 -c
