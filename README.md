# Phát Triển Hệ Thống Bẫy Phát Hiện Côn Trùng Thông Minh

> **Đồ án Tốt nghiệp / Báo cáo Thực tập** > _Tối ưu hóa hệ thống nhận diện và đếm côn trùng sử dụng Trí tuệ nhân tạo (AI) trên thiết bị biên._

## 📖 Giới thiệu (Introduction)

Dự án này tập trung vào việc **phát triển và tối ưu hóa** hệ thống bẫy côn trùng thông minh đã có. Mục tiêu chính là nâng cao hiệu suất nhận diện, cải thiện tốc độ xử lý trên phần cứng nhúng và hoàn thiện cơ chế hoạt động tự động.

Hệ thống sử dụng các công nghệ Deep Learning tiên tiến nhất hiện nay (YOLOv11) để nhận dạng và đếm số lượng côn trùng trong thời gian thực, phục vụ cho việc giám sát và cảnh báo trong nông nghiệp công nghệ cao.

### Mục tiêu dự án:

- Nghiên cứu cơ sở lý thuyết về nhận dạng đối tượng và xử lý ảnh.
- Kế thừa và đánh giá hiệu quả của các mô hình cũ.
- **Tối ưu hóa hệ thống:** Nâng cấp mô hình AI lên YOLOv11, tối ưu code để chạy mượt mà trên Jetson Orin Nano Super.
- Xây dựng mô hình nhận dạng và đếm côn trùng với độ chính xác cao hơn.

---

## 🛠️ Phần cứng (Hardware)

Hệ thống được vận hành trên nền tảng tính toán biên mạnh mẽ:

- **Bộ xử lý trung tâm:** NVIDIA Jetson Orin Nano Super.
- **Thu nhận hình ảnh:** Raspberry Pi Camera (Kết nối qua cổng CSI/MIPI).
- **Cơ cấu chấp hành:** Động cơ Servo (Điều khiển di chuyển camera).
- **Mạch điều khiển động cơ:** Module PCA9685 (Giao tiếp I2C).

---

## 💻 Công nghệ & Phần mềm (Software & Tech Stack)

- **Ngôn ngữ lập trình:** Python 3.x
- **Core AI Model:** [YOLOv11](https://github.com/ultralytics/ultralytics) (State-of-the-art Object Detection).
- **Thư viện xử lý ảnh:** OpenCV.
- **Thư viện phần cứng:** Jetson GPIO, Adafruit_CircuitPython_PCA9685.
- **Hệ điều hành:** Linux (Ubuntu trên Jetson).

---

## 🌟 Tính năng chính (Key Features)

1.  **Nhận diện Real-time:** Phát hiện côn trùng với tốc độ xử lý cao nhờ YOLOv11 và sức mạnh của Jetson Orin.
2.  **Đếm số lượng tự động:** Tự động thống kê số lượng côn trùng đã vào bẫy.
3.  **Điều khiển cơ khí:** Tự động kích hoạt Servo để cải thiện độ chính xác trong quá trình nhận diện côn trùng.
4.  **Hệ thống tối ưu:**

---

## 👥 Tác giả & Hướng dẫn (Credits)

Dự án được thực hiện bởi:

- **Sinh viên thực hiện:** Phan Văn Trường
- **Giảng viên hướng dẫn:** PGS. TS. Đoàn Thanh Nghị

---

## 📸 Demo (Optional)
