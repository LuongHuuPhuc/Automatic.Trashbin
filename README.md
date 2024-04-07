# Automatic Trashbin Overview
***
## **Đây là một dự án đơn giản sử dụng được tạo ra để tăng sự tiện lợi cho việc đổ rác bình thường**
    php echo printf (Arduino.Trashbin) 
### *Một Số Ưu Điểm*
* Thùng rác có thể nhận diện được vật thể từ khoảng cách được thiết lập (5cm - 80cm).
* Nguồn cấp từ pin 9v với dòng xả 900mAh, thời gian dùng tối đa lên đến 1 tuần không cần sạc.
### *Yêu cầu phần cứng* 
- Arduino UnoR3, Nano, Mega,...
- Cảm biến siêu âm HC-SR04.
- Động cơ servo micro SG90 180 độ (Có thể thay đổi động cơ tùy theo nhu cầu).
- Dây cáp TestBoard.
***
### *Yêu cầu phần mềm*
-Arduino IDE
## Sơ đồ kết nối chân 
![Sơ đồ](https://github.com/LuongHuuPhuc/Automatic.Trashbin/assets/156191563/235ae30f-5c02-4974-bc8d-9e61e0dc88d0)

| Arduino Uno R3 | Ultrasonic sensor | Servo |
|:---------------|:------------------|:------|
| Gnd            | Gnd               | Gnd   |
| D8             | EchoPin           |       |
| D9             | TrigPin           |       |
| 3.3v-5v        | Vcc               | Vcc   |
| D7             |                   | Pwm   |
