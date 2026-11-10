Báo cáo TH5
Trong bài thực hành này, hệ thống IoT được xây dựng theo mô hình thiết bị - broker - dashboard. Thiết bị ESP32 thu thập dữ liệu cảm biến và gửi dữ liệu lên MQTT Broker. Broker tiếp nhận và phân phối dữ liệu đến Dashboard để người dùng giám sát theo thời gian thực.

Một yêu cầu quan trọng của hệ thống IoT là khả năng hoạt động ổn định khi mạng không ổn định. Trong quá trình thực hiện, chức năng tự động kết nối lại được mô phỏng để xử lý tình huống mất kết nối mạng. Sau khi kết nối bị gián đoạn, thiết bị thực hiện quá trình kết nối lại và tiếp tục truyền dữ liệu.

Hướng mở rộng được lựa chọn là tích hợp nền tảng Cloud như Azure IoT Hub hoặc AWS IoT. Khi triển khai trên Cloud, dữ liệu có thể được lưu trữ lâu dài, phân tích theo thời gian thực và quản lý số lượng lớn thiết bị từ xa. Ngoài ra, hệ thống có thể được mở rộng bằng Dashboard Web hoặc Mobile để theo dõi và điều khiển thiết bị ở mọi nơi. Giải pháp này phù hợp với các ứng dụng giám sát môi trường, nông nghiệp thông minh và nhà thông minh.
