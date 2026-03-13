1. ฝั่ง DEV (ต้นทาง - Environment 1)

IP / Domain: ที่อยู่ของเครื่อง Gateway ฝั่ง DEV (เช่น 10.0.0.10)   
IP : 172.188.100.57

Username: ไอดีที่มีสิทธิ์สั่ง Export (ตั้งค่าใน GitHub Secret ชื่อ DEV_USERNAME)

Password: รหัสผ่านของไอดีนั้น (ตั้งค่าใน GitHub Secret ชื่อ DEV_PASSWORD)

2. ฝั่ง NON-PROD (ปลายทาง - Environment 2)

IP / Domain: ที่อยู่ของเครื่อง Gateway ฝั่ง NON-PROD (เช่น 10.0.0.20)
IP : 20.198.251.142

Username: ไอดีที่มีสิทธิ์สั่ง Import (ตั้งค่าใน GitHub Secret ชื่อ NONPROD_USERNAME)

Password: รหัสผ่านของไอดีนั้น (ตั้งค่าใน GitHub Secret ชื่อ NONPROD_PASSWORD)