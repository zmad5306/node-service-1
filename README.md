```
npm i
sudo cp node-service-1.service /etc/systemd/system/node-service-1.service
sudo systemctl enable node-service-1.service
sudo systemctl start node-service-1.service
systemctl -l status node-service-1
```
