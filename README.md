# ROBOT

Arduino / ESP32 → nên dùng C++

Ưu điểm	Nhược điểm
Tương thích tốt với mạch điều khiển như Arduino Uno, ESP32	Không tiện cho xử lý hình ảnh, AI
Dễ điều khiển LED, servo, cảm biến	Code dài hơn, không thân thiện cho AI
Chạy nhanh, nhẹ, phù hợp thiết bị hạn chế tài nguyên	Hạn chế về thư viện AI, xử lý ảnh

Raspberry Pi hoặc máy tính nhỏ → nên dùng Python
Ưu điểm	Nhược điểm
Có thể xử lý hình ảnh, giọng nói, nhận diện cảm xúc người dùng	Chạy chậm hơn, cần thiết bị mạnh hơn
Rất nhiều thư viện AI: OpenCV, TensorFlow, SpeechRecognition	Cần học cách điều khiển GPIO nếu điều khiển servo, LED
Dễ viết, ngắn gọn, dễ mở rộng	Không phù hợp cho các mạch đơn giản như Arduino Uno
