ARG BASE_IMAGE=ubuntu:resolute

FROM $BASE_IMAGE
COPY get-package-version.sh /get-package-version.sh
ENTRYPOINT ["/get-package-version.sh"]