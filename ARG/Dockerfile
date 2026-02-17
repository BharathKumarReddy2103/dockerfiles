ARG version
FROM almalinux:${version:-9}
ENV course="devsecops" \
    duration="120hrs"
ARG trainer=bharathkumarreddyn
ENV trainer=$trainer
RUN echo "Hi, Course is: ${course}, duration is: ${duration}, trainer is: ${trainer}, version: ${version}"
CMD ["sleep", "1100"]