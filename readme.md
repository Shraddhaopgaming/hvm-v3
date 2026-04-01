> **1. sudo apt update
> 
> 2. sudo apt install git -y
> 
> 3. git clone https://github.com/Shraddhaopgaming/hvm-v3
> 
> 4. sudo apt install python3-pip -y
> 
> 5. cd hvm-v3
> 
> 6 (cheack folder are there by this) ls -l
> 
> 7. pip3 install flask flask-socketio flask_login docker paramiko python-dotenv psutil flask-limiter ecdsa
> 
> 8. Connect Domain
> 
> 9. python3 hvm.py**
> 
> 10.docker network create vps-net
> 
> docker run --net vps-net --privileged --device /dev/kvm -it <image_name>
> 
> 11. docker ps -a
> 
12. rm -rf * (remove all files and foulders)
>
> localhost:3000 (in this url use in cloudflare tunnle
