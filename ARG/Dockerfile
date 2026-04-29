ARG version=latest 
# latest image
FROM almalinux:${version}
#FROM almalinux:${version:-9} # this is default version
ARG course="DevOps with Docker" \
    author="Matthews" \
    company="inspiredevops"

RUN echo "Course: $course, Author: $author, Company: $company, version: ${version}"
CMD ["sleep", "100"]

# docker build -t env:v1 --build-arg version=8 . 
