FROM almalinux:9
RUN useradd expense
RUN mkdir /tmp/docker
WORKDIR  /tmp/docker
RUN pwd
RUN echo "Hello" > hello.txt
CMD ["sleep", "100"]
USER expense
