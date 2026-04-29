# On run
# FROM almalinux:9
# RUN mkdir /tmp/docker
# RUN cd /tmp/docker 
# RUN pwd
#RUN echo "Hello World" > hello.txt # This will create hello.txt in the current directory which is /tmp/docker
#RUN echo "Hello World" > /tmp/docker/hello.txt # This will create hello.txt in the current directory which is /tmp/docker
# CMD ["sleep", "100"]

# on workdir
FROM almalinux:9
RUN mkdir /tmp/docker
WORKDIR /tmp/docker 
RUN pwd
RUN echo "Hello World" > hello.txt 
CMD ["sleep", "100"]