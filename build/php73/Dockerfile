ARG centos=7.9.2009
ARG image=php-igbinary-7.3

FROM aursu/peclbuild:${centos}-${image}

RUN yum -y --enablerepo=bintray-php73custom install \
        php-pecl-msgpack-devel \
    && yum clean all && rm -rf /var/cache/yum /var/cache/dnf
