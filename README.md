# 🧨 Minesweeper
Một phiên bản Minesweeper cổ điển, được lập trình bằng C++ và SDL2. 
![screenshot](https://drive.google.com/uc?export=view&id=1bRl4tgS47rMFXpEJrkqJS7VcatkY8Dqq)


--- 
🎮 Gameplay
- Chuột trái: mở ô.
- Chuột phải: đặt cờ, gỡ cờ.
- Nút “Start”: bắt đầu game.
- Nút “Restart”: tạo ván mới.

🎯 Mục tiêu:
Mở toàn bộ các ô an toàn mà không kích hoạt bất kỳ quả mìn nào.

---
🧱 Dependencies
SDL2
SDL2_image
SDL2_ttf 

---
🔍 Main Logic
- Khởi tạo Game: Tạo bản đồ, đặt bom và render giao diện.
- Render giao diện: Gọi Render_Headbar() và Render_Map() để hiển thị thanh headbar và bản đồ.
- Bắt sự kiện SDL: Vòng lặp chính xử lý sự kiện chuột (mở ô, đặt cờ).
- Xử lý chuột trái: Mở ô, hoặc thực hiện thao tác khởi động lại khi chọn RESTART.
- Xử lý chuột phải: Đặt cờ, gỡ cờ.
- Kiểm tra điều kiện chiến thắng: Nếu số ô chưa mở bằng 0, gọi Victory() để kết thúc game.
- Giải phóng và kiểm tra bộ nhớ: Kết thúc game. Gọi _CrtDumpMemoryLeaks().

---
▶️ Demo
Video demo: https://drive.google.com/file/d/1BngcN2Oe0Vii0GmXGsQFn74MKFjbZYVw/view?usp=sharing

![Màn hình mặc định](https://drive.google.com/uc?export=view&id=169Ow3_gTnip6rdYE6pVltEcdp4nHsB8c)

![Chọn ô bom](https://drive.google.com/uc?export=view&id=1ilI87mGBYPsMaYuiTwUNulGVMNlwdeWo)

