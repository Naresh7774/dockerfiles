ARG VERSION
FROM almalinux:${VERSION:-9}
ARG Name="Naresh" \
    Degree="Btech"
ENV Name=${Name}
RUN echo "NAME: ${Name}, DEGREE: ${Degree}, Version: ${VERSION}"
CMD ["sleep", "1000"]