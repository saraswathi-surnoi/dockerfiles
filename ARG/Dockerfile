ARG version
FROM almalinux:${version:-9}
ARG course= "devops" \
    duration ="120hrs"
ENV duration=$duration
RUN echo "course: $course, duration: $duration"
CMD ["sleep","100"]
