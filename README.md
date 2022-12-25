<p style="font-size:14px" align="right">
<a href="https://t.me/Bal33671" target="_blank">Reach me on telegram <img src="https://user-images.githubusercontent.com/50621007/183283867-56b4d69f-bc6e-4939-b00a-72aa019d1aea.png" width="30"/></a>
<a href="https://twitter.com/Bal3367" target="_blank">Visit my twitter <img src="https://user-images.githubusercontent.com/110718880/204088136-3e807cf8-1fc4-4a7d-a833-d58180e36413.png" width="30"/></a>
</p>



# Tutorial Node Gaga

Dokumen Official :
> [Doc Offical](https://docs.gaganode.com/ "Doc Offical")

![image](https://user-images.githubusercontent.com/119092888/209459702-642e6321-e508-401f-b458-7f0e1ca2b662.png)

# Spesifikasi VPS
4 Core CPU

8 GB RAM

# Langkah - langkah install node 
# Download & install
```console
curl -o app-linux-amd64.tar.gz https://assets.coreservice.io/public/package/22/app/1.0.3/app-1_0_3.tar.gz && tar -zxf app-linux-amd64.tar.gz && rm -f app-linux-amd64.tar.gz && cd ./app-linux-amd64 && sudo ./app service install
```
# Start service
```console
sudo ./app service start
```
# Check app status
```console
./app status
```
output harus 

`check gaganode status is RUNNING`
# Set token
```console
sudo ./apps/gaganode/gaganode config set --token=<tokenmu>
```
# Restart service
```console
restart app
```
