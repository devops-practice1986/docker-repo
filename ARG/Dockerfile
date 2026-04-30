ARG version=latest 
# latest image
FROM almalinux:${version}
#FROM almalinux:${version:-9} # this is default version
ARG course="DevOps with Docker" \
    author="Matthews" \
    company="inspiredevops"

# it can be accessed in container as environment variable
ENV course=${course} \ 
    author=${author} \
    company=${company} \
    version=${version}

RUN echo "Course: $course, Author: $author, Company: $company, version: $version" 
CMD ["sleep", "100"]

# docker build -t env:v1 --build-arg version=8 . 
