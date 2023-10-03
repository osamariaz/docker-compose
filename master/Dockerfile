FROM jenkins/jenkins
USER root
RUN apt-get update  && \ 
    apt install -y net-tools sudo git apache2
RUN service apache2 enable && \ service apache2 start
