ARG version 
# latest image
FROM almalinux:${version}
ARG course="DevOps with Docker" \
    author="Matthews" \
    company="inspiredevops"

RUN echo "Course: $course, Author: $author, Company: $company"
CMD ["sleep", "100"]

# docker build -t env:v1 --build-arg version=8 . 
# 