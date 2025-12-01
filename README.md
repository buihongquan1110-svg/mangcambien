# 🚪 Smart Door System – Face Recognition + Bluetooth/WiFi  
### ESP32 • Raspberry Pi • Blynk • AI – OpenCV

---

## 📌 Giới thiệu
Dự án xây dựng mô hình **cửa thông minh** kết hợp giữa:
- **ESP32**: điều khiển cửa qua WiFi/Blynk và cảm biến siêu âm.
- **Raspberry Pi**: nhận diện khuôn mặt bằng **AI – OpenCV**.
- **Camera CMOS**: thu hình ảnh realtime.
- **Servo/Motor**: đóng mở cửa tự động.

Hệ thống hoạt động theo cơ chế:
1. Phát hiện người → ESP32 gửi tín hiệu sang RPi.  
2. RPi nhận diện khuôn mặt → phản hồi kết quả.  
3. Nếu đúng người → ESP32 mở cửa → tự đóng sau 5 giây.  
4. Người dùng cũng có thể mở cửa qua ứng dụng **Blynk**.

---

## 🎯 Mục tiêu đề tài
- Xây dựng hệ thống cửa tự động điều khiển qua Bluetooth/WiFi.  
- Tích hợp AI nhận diện khuôn mặt nâng cao bảo mật.  
- Thiết kế mô hình nhà thông minh thu nhỏ dễ demo.  
- Đảm bảo hệ thống ổn định, trực quan, dễ mở rộng.

---

## 🧩 Kiến trúc hệ thống

### 🔹 1. ESP32 – IoT
- Điều khiển servo mở/đóng cửa.  
- Kết nối Blynk qua WiFi.  
- Đọc cảm biến siêu âm để phát hiện người.  
- Hiển thị trạng thái lên LCD 1602 I2C.  
- Gửi/nhận tín hiệu với Raspberry Pi qua GPIO.

### 🔹 2. Raspberry Pi – AI
- Sử dụng OpenCV để phát hiện & nhận dạng khuôn mặt.  
- Thu hình từ camera CMOS USB.  
- Xác thực người dùng → gửi tín hiệu về ESP32.
