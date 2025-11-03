FROM lscr.io/linuxserver/webtop:fedora-xfce

USER abc

RUN sudo dnf install zip -y
RUN sudo dnf install dotnet-sdk-8.0.x86_64 -y
RUN sudo dnf install libadwaita.x86_64 -y
RUN sudo dnf install libglvnd-gles.x86_64 -y
RUN sudo dnf install net-tools -y

USER root

EXPOSE 3000
EXPOSE 3001
