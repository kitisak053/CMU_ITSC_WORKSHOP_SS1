# CMU_ITSC_WORKSHOP_SS1

GIT REPOSITORY นี้ ใช้สำหรับฝึก WorkShop ที่ 1 การใช้ Dockerfile และ Docker Compose กับ .NET CORE 2.2 และDeploy บน Docker Server ขั้นต้น
ซึ่งเป็น Pre request ของ WorkShop ที่ 2 

1 เข้าไปที่Server Workshop <br/>
  terminal SSH UserXX@10.110.x.x <br/>
2 GIT CLONE https://github.com/best0032001/CMU_ITSC_WORKSHOP_SS1.git <br/>
3 CD CMU_ITSC_WORKSHOP_SS1 <br/>
4 docker-compose up -d --build <br/>
5 docker ps เพื่อตรวจสอบว่า มี container run ที่ port 81 <br/>
6 ลองเรียก api  http://10.110.x.x:81/api/values <br/>
