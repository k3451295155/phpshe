
# Denial of service vulnerability exists in phpshecms verification code

Program download address. http://www.phpshe.com/down/phpshe1.8.rar
## First go to the registration page and click refresh verification code
![image](https://user-images.githubusercontent.com/56090996/150913213-8b52a861-9fda-403c-b564-2f8d3d35acd8.png)
## Grab the packet and modify its l(length) and h(height)
![image](https://user-images.githubusercontent.com/56090996/150913525-f5e82f8d-2fe5-4b99-b3b7-0ffc4481d55f.png)

![image](https://user-images.githubusercontent.com/56090996/150913675-e0736be5-ff07-4a9c-8768-76b30f39134b.png)

## 50 threads send 100 packets
![image](https://user-images.githubusercontent.com/56090996/150914155-28eea49a-9fc8-40cb-8995-7e203fdc6344.png)

![image](https://user-images.githubusercontent.com/56090996/150914177-9cd2fba3-a2e3-4e7e-8760-a88842f3229b.png)

## Enter the server and find the cpu usage %99
![image](https://user-images.githubusercontent.com/56090996/150914104-2cbf7648-c0f1-4c48-8132-df1a0a52dc33.png)

