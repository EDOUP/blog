1. centos常用开发工具集

``` dockerfile
FROM centos
MAINTAINER edoup

WORKDIR /usr/local
RUN yum -y install vim 
RUN yum -y install net-tools
RUN yum -y install java-11-openjdk.x86_64
CMD /bin/bash
```

