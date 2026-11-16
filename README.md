**SƠ ĐỒ LUỒNG XỬ LÝ/THUẬT TOÁN VÀ CÁC TÍNH NĂNG CỦA GAME TETRIS**

**1. SƠ ĐỒ LUỒNG XỬ LÝ**

https://lucid.app/lucidspark/e8a1c5b6-daa8-490e-b0ba-abc37513d8ef/edit?viewport_loc=-277%2C-21%2C3337%2C1795%2C0_0&invitationId=inv_f70188fe-1647-44cd-a087-01fc26725194

**2. CÁC TÍNH NĂNG CỦA GAME TETRIS**

**2.1. Các tính năng bắt buộc (Core Features)**
- Khởi tạo bàn chơi: Thiết lập lưới ma trận trò chơi và hệ thống tường bao quanh.

- Sinh khối ngẫu nhiên: Khởi tạo các khối hình học (Tetrimino) ngẫu nhiên xuất hiện tại vị trí chuẩn bị.

- Di chuyển: Hỗ trợ điều khiển khối di chuyển sang trái, sang phải và rơi xuống.

- Xoay khối: Thay đổi hướng xoay của khối theo thời gian thực.

- Kiểm tra va chạm: Phát hiện và ngăn chặn va chạm giữa khối đang rơi với biên bàn chơi hoặc các khối đã được cố định.

- Cố định khối: Gắn kết và lưu giữ vị trí khối vào ma trận bàn chơi khi nó không thể di chuyển xuống thêm.

- Xóa hàng: Quét và phát hiện các hàng đã được lấp đầy, thực hiện xóa hàng, dồn các hàng phía trên xuống và cập nhật điểm số cơ bản.

- Kiểm tra kết thúc trò chơi (Game Over): Xác định điều kiện dừng game khi không còn không gian sinh khối mới tại vị trí xuất phát.

**2.2. Các tính năng mở rộng (Advanced Features)**
- Tính điểm: Xây dựng hệ thống tính điểm tương ứng với số hàng được xóa cùng lúc.

- Hiển thị khối tiếp theo (Next Block): Cho phép người chơi nhìn trước hình dạng khối sẽ xuất hiện kế tiếp để lên chiến thuật.

- Tạm dừng trò chơi (Pause): Tạm dừng và tiếp tục vòng lặp trò chơi khi người dùng có nhu cầu.

- Lưu trữ thứ hạng (High Scores): Ghi nhận và lưu lại điểm số cao nhất của người chơi.

- Theo dõi thời gian: Đếm và hiển thị thời gian diễn ra ván chơi.

- Cất khối tạm thời (Hold Piece): Cho phép người chơi cất giữ tạm thời khối đang xuất hiện vào kho lưu trữ hữu hạn (có giới hạn số lần sử dụng) để lấy ra dùng khi cần thiết.
