# BoardC25_testing
test board C25
## Tình hình test board
LCD và TFT hoạt động ổn định ,
Button 2 và 3 có hiện tượng nhiễu nặng  
2 led test của stm32 và esp32 hoạt động bình thường 
các nút reset , boot hoạt động bình thường 
Relay không kích được - hoặc do em không biết cách kích 
Ds3231 hoạt động bình thường (trong trường hợp không gắn mpu6050)
uart1 hoạt động bình thường .

### Lỗi đáng chú ý :
Button 2 và 3 bị nhiễu nặng - không rõ lý do.
Relay không kích được - có thể do bản thân người thử nghiệm không biết kích .

### Các khối chưa test : 
hc05 
giao tiếp giữa esp32 và stm32 
các ngoại vi trên 2 hàng header  

### Dự đoán kết quả test các khối chưa test : hoạt động bình thường cả hc05 , stm32 <-> esp và ngoại vi trên 2 hàng header
