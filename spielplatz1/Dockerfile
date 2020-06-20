FROM centos:centos7
RUN groupadd -g 1999 appuser && useradd -r -u 1999 -g appuser appuser
USER appuser
CMD ["bin/bash"]

