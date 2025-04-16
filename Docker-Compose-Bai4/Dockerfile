# Dùng image Node chính thức
FROM node:18

# Tạo thư mục làm việc trong container
WORKDIR /app

# Copy file cấu hình
COPY package*.json ./

# Cài đặt dependencies
RUN npm install

# Copy mã nguồn vào container
COPY . .

# Expose cổng ứng dụng
EXPOSE 3000

# Lệnh chạy app
CMD ["npm", "start"]
