# BoardC25_testing
test board C25
## Tình hình test board
LCD và TFT hoạt động ổn định ,
2 led test của stm32 và esp32 hoạt động bình thường 
các nút reset , boot hoạt động bình thường 
Relay không kích được - hoặc do em không biết cách kích 
Ds3231 hoạt động bình thường (trong trường hợp không gắn mpu6050)
uart1 hoạt động bình thường .

### Lỗi đáng chú ý :
Relay không kích được - có thể do bản thân người thử nghiệm không biết kích .
MPU6050 và Ds3231 trùng địa chỉ 

### Các lỗi khác :
Lỗi button2 , 3 , 1 không có trở kéo lên hoặc xuống mặc định - cần phải đặt trở kéo lên , kéo xuống bằng code arduino ide - hoặc ioc file trên stm32

### Các khối chưa test : 
hc05 
giao tiếp giữa esp32 và stm32 
các ngoại vi trên 2 hàng header  

### Dự đoán kết quả test các khối chưa test : 
hoạt động bình thường cả hc05 , stm32 <-> esp và ngoại vi trên 2 hàng header
button 1 có thể bị nhiễu tương tự button 2 và 3 

# Video :
## Nhiễu button 2 và 3
https://github.com/user-attachments/assets/6cc48980-1958-4925-992b-9ae5cc76ae09


## Không kích được relay 

https://github.com/user-attachments/assets/5924efae-9fdb-44e8-9d70-542511f10e79
