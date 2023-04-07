# Stimulate-26-character-keyboard
# Yêu cầu : 
-  Thiết kế mạch điện tử sử dụng vi xử lý 8051 và một vi mạch 74’138 cùng các cổng logic, vi mạch cần thiết khác để điều khiển LCD và giao tiếp với 26 nút nhấn đơn tại địa chỉ được cho như sau:
-  Địa chỉ truy suất	Ngoại vi giao tiếp
      0000H – 7FFFH	Giao tiếp với 27 nút nhấn: được đặt tên từ A đến Z (26 nút) và một nút Shift.
      8000H – AFFFH	Giao tiếp với LCD.
 -  Vẽ mô phỏng trên Proteus, lập trình cho 8051 thực hiện chương trình đọc trạng thái của các nút nhấn và hiển thị ký tự tương ứng trên LCD: khi nút shift không nhấn ký tự hiển thị là chữ thường, khi nút nhấn được nhấn ký tự hiển thị là chữ in hoa (nhấn cả 2 phím). Các ký tự hiển thị trên LCD được hiển thị từ trái sang phải, bắt đầu từ ô bên tay trái ngoài cùng, phía trên, sau khi ghi hết 1 hàng đầu tiên thì tự động xuống hàng, sau khi ghi hết hàng thứ 2, tự động xóa màn hình và bắt đầu tại từ ô bên tay trái ngoài cùng phía trên.
