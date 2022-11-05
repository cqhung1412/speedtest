# Raspberry Pi Network Speedtest

### Install
```cmd
sudo apt install -y python-pip
sudo pip install -r requirements.txt
```

Install [Grafana](https://grafana.com/tutorials/install-grafana-on-raspberry-pi/) 

Install [InfluxDB](https://pimylifeup.com/raspberry-pi-influxdb/) 

### Crontab
```cmd
crontab -e
*/15 * * * * python3 /home/pi/speedtest/rpi-speedtest.py
```