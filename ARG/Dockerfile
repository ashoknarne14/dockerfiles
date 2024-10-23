ARG version
FROM almalinux:${version}
ARG course="DevOps with AWS" \
    Duration="120hrs"
ENV course=$course \
    Duration=$Duration
RUN echo "Course: $course, Duration: $Duration, Version: $version"
CMD ["sleep", "100"]