FROM opennms-base-deb

MAINTAINER ranger@opennms.org

# packages required by OpenNMS build scripts
RUN apt-get -y install perl-base perl-modules

COPY opennms-build-installer.sh /docker-entrypoint-initdb.d/99-opennms-build-installer.sh
