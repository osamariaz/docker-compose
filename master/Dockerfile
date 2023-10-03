FROM jenkins/jenkins
USER root
RUN apt install update -y && \ 
    apt install net-tools && \ apt install sudo -y && \ apt install git -y && \ apt install apache2
RUN service apache2 enable && \ service apache2 start
USER jenkins 
