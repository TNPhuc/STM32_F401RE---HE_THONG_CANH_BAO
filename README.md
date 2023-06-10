# HỆ THỐNG CẢNH BÁO SỬ DỤNG STM32 NUCLEO F401RE

## THÀNH VIÊN
> Chủ trì đề tài: Trần Nguyễn Phúc
> 
> Thực hiện: Trần Nguyễn Phúc - Võ Thị Hồng Ánh - Phạm Đặng Kiều Oanh
## MÔ TẢ HỆ THỐNG
- Ngôn ngữ sử dụng: C
- Phần mềm: STM32CubeIDE
- Linh kiện sử dụng: Board mạch STM32 Nucleo F401RE, dây cáp nạp, nút bấm, LED, còi chíp, Relay, khóa điện tử, nguồn, cảm biến nhiệt độ LM35, màn hình LCD 16x2 I2C, dây dẫn.
- Tóm tắt hoạt động: Khi nhiệt độ thu được từ cảm biến trên 70 độ, còi chíp kêu, sáng đèn màu đỏ kèm hiển thị lên LCD "NHIET DO CAO" nhằm cảnh cáo có hỏa hoạn xảy ra.
Khi nhấn nút số 1 được giả lập nút bấm chuông cửa, đèn led màu vàng sẽ sáng, còi chíp kêu kèm hiển thị lên màn hình LCD "CO NGUOI" nhằm thông báo cho chủ nhà biết có người ngoài cửa đang nhấn chuông.
Khi nhấn nút số 2 được giả lập nút mở cửa, RELAY lúc này từ trạng thái đóng sẽ chuyển sang trạng thái mở để mở ổ khóa điện tử, khi nút số 2 được nhấn một lần nữa RELAY sẽ chuyển từ trạng thái mở sang trạng thái đóng để đóng ổ khóa điện tử.
