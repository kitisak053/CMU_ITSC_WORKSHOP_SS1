# CMU_ITSC_WORKSHOP_SS1

GIT REPOSITORY นี้ ใช้สำหรับฝึก WorkShop การใช้ Dockerfile และ Docker Compose กับ .NET CORE 2.2 และDeploy บน Docker Server

1 เข้าไปที่Server Workshop 
  terminal SSH UserXX@10.110.x.x
2 GIT CLONE https://github.com/best0032001/CMU_ITSC_WORKSHOP_SS1.git
3 CD CMU_ITSC_WORKSHOP_SS1
4 docker-compose up -d --build
5 docker ps เพื่อตรวจสอบว่า มี container run ที่ port 81
6 ลองเรียก api  http://10.110.x.x:81/api/values
