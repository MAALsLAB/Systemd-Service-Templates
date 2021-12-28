# How to Create a Systemd Service in Linux

1. cd /etc/systemd/system/
2. touch Service-Name.service
3. use one of the templates
4. sudo systemctl daemon-reload
5. sudo systemctl start Service-Name.service
6. sudo systemctl status Service-Name.service
7. sudo systemctl enable Service-Name.service
8. sudo systemctl disable Service-Name.service
