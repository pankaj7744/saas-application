I am working my own cloud project and named it Hooper. It is a basic cloud having the following services :

    Software as a service (SAAS)
    Storage as a service(STAAS). It has again two type of services :
        Object Storage
        Block Storage
    Infrastructure as a service (IAAS)
    Container as a service (CAAS)
    Platform as a service (PAAS)

Background technologies used :

    For SAAS i used X11 Forwarding property of SSH protocol to provide software to clients.
    Storage :
        For object storage i have used Glusterfs.
        For block storage i have used iSCSI protocol.
    For infrastructure as a service i used qemu-kvm for providing virtualized cloud OS to the client and to provide it on browser i used noVNC.
    For container as a service i used Dockers and to provide it to clients browser i used shellinabox tool.
    Again for PAAS i used Dockers.

For Web Application :

    Back-end:- Python CGI
    Front-end:- HTML and CSS Database:- MongoDB
