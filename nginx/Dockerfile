# ใช้ official Nginx image เป็น base
FROM nginx:alpine

# ลบไฟล์ config เริ่มต้นของ Nginx
RUN rm /etc/nginx/conf.d/default.conf

# คัดลอกไฟล์ config ที่เราสร้างขึ้นไปแทนที่
COPY nginx.conf /etc/nginx/conf.d/
