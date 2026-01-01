# CanhBaoSuCo

HỆ THỐNG CẢNH BÁO SỰ CỐ GIAO THÔNG

Hệ thống hỗ trợ người dùng di chuyển an toàn khi kết hợp với GoogleMap:
- Thấy được các sự cố xung quanh trong bán kính R
- Đăng nhập bằng google để báo cáo sự cố
- Báo cáo sự cố hỗ trợ cộng đồng và sẽ được thưởng lợi nhuận sau nhiều báo cáo
- Ra tín hiệu cứu trợ, trụ sở gần nhất sẽ nhận tín hiệu SOS

Công nghệ: Kotlin - Jetpack Compose, Java SpringBoot, Docker, MySQL
Tools: Android Studio, Visual Studio Code, Docker Desktop

Quy trình khởi động:
Bước 1: Clone toàn bộ code về, hiện tại admin đang ở cổng 8080, database ở cổng 8081, có thể điều chỉnh tùy ý.
Bước 2: Khởi động VSCode và Docker Desktop, khởi động docker ngay nơi chứa docker.yml
Bước 3: Cài Maven nếu chưa có, chạy lệnh mvn spring-boot:run. 
Bước 4: Khởi động Android Studio, kết nối với điện thoại thật (có nhiều cách) và bấm Run.
