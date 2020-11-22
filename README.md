# platform สำหรับ implement all in one apigateway + microservice + loadbalance + web application firewall

# ansible-dev
- ใช้ได้เฉพาะ nginx-plus เท่านั้น เพราะบาง feature ไม่รองรับบน nginx version ปกติ

- ก่อนการใช้งานต้องระบุชื่อ hosts ปลายทางที่ inventory ให้ถูกต้อง

- ระบุ ip address ของ virtual ip, apigateway master node ip, และ apigateway backup node ip ด้วย

- ภายใน platform ติดต่อกันด้วย hostname จึงต้อง map ip เครื่องแต่ละเครื่องให้ตรงกับ hostname โดยดูชื่อ hostname ได้จากไฟล์ inventory/hosts

