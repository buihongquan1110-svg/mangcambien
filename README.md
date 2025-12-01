🚪 HỆ THỐNG CỬA TỰ ĐỘNG NHẬN DIỆN KHUÔN MẶT + BLUETOOTH/WIFI

(ESP32 – Blynk – Raspberry Pi – AI Face Recognition)

📌 Giới thiệu

Đề tài xây dựng mô hình cửa thông minh sử dụng ESP32 kết hợp điều khiển từ xa thông qua WiFi/Blynk, đồng thời tích hợp AI nhận diện khuôn mặt chạy trên Raspberry Pi nhằm tăng tính an toàn và tự động hóa trong hệ thống nhà thông minh (Smart Home).

Hệ thống cho phép mở cửa bằng:

Ứng dụng Blynk.

Nhận diện chủ nhân qua Bluetooth/WiFi.

Nhận dạng khuôn mặt bằng AI.

🎯 Mục tiêu đề tài

Xây dựng mô hình cửa tự động thông minh điều khiển qua WiFi/Bluetooth.

Ứng dụng AI để nhận diện khuôn mặt người dùng.

Hiển thị trạng thái cửa và thông số lên LCD.

Tạo mô hình trực quan phục vụ trình bày và demo.

Đảm bảo hoạt động ổn định, an toàn và dễ mở rộng trong tương lai.

🧩 Cơ sở lý thuyết
🔹 IoT & Nhà thông minh

IoT là mạng lưới thiết bị thông minh có khả năng kết nối và trao đổi dữ liệu qua Internet. Trong nhà thông minh, IoT được ứng dụng để điều khiển đèn, cửa, an ninh, điều hòa,… giúp tăng tiện lợi và hiệu quả.

🔹 ESP32

Vi điều khiển 32-bit tích hợp WiFi + Bluetooth.

CPU dual-core 240 MHz, nhiều giao tiếp (GPIO, ADC, PWM, I2C…).

Đóng vai trò trung tâm điều khiển cửa và kết nối Internet.

🔹 Nền tảng IoT Blynk

Giao diện điều khiển thiết bị từ xa qua Internet.

Kết nối ESP32 ↔ Cloud ↔ Smartphone.

Hỗ trợ nút nhấn, hiển thị dữ liệu, log sự kiện.

🔹 Động cơ Servo

Điều khiển đóng/mở cửa bằng góc quay chính xác thông qua tín hiệu PWM.

🔹 Nhận diện khuôn mặt AI (Raspberry Pi)

Camera CMOS ghi hình → Raspberry Pi xử lý bằng OpenCV.

Phát hiện bằng Haar Cascade.

Nhận dạng bằng LBPH Face Recognizer.

Gửi tín hiệu xác thực về ESP32 thông qua GPIO.
