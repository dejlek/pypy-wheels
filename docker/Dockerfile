FROM pypywheels/manylinux2010-pypy_x86_64
LABEL maintainer="anto.cuni@gmail.com"

# this is needed for numpy and scipy XXX: investigate whether we need to use
# this to get a newer version of the library?
# https://fedoraproject.org/wiki/EPEL
RUN yum install -y openblas-devel

