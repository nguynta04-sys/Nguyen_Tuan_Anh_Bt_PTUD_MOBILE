# Nguyen_Tuan_Anh_Bt_PTUD_MOBILE
## MÔN HỌC: PHÁT TRIỂN ỨNG DỤNG TRÊN THIẾT BỊ DI ĐỘNG
## BÀI TẬP LỚN:
## Nguyễn Tuấn Anh 
## MSSV K225480106002
## Lớp K58_KTP 


1. Viết phần mềm trên công cụ Mit App inventor

- Nhìn sang cột ngoài cùng bên phải (Properties), tìm thuộc tính AlignHorizontal (hiện đang là Left : 1).

- Bấm vào đó và đổi thành Center : 3 để mọi thứ chúng ta kéo vào sẽ tự động căn giữa cho đẹp.
<img width="1910" height="1080" alt="image" src="https://github.com/user-attachments/assets/af8a9b2e-7322-497b-b011-376540d9fea8" />

- Ở cột bên trái ngoài cùng (User Interface), cuộn xuống dưới một chút tìm mục Layout (ngay dưới User Interface). Bấm vào mục Layout đó.

- Kéo thành phần tên là VerticalArrangement (Bố cục dọc) thả vào trong màn hình điện thoại ảo ở giữa.

- Nhìn sang cột Properties bên phải của cái VerticalArrangement vừa kéo vào:

- Tìm thuộc tính Width -> Bấm chọn Fill parent -> Bấm OK (để nó dãn hết chiều ngang).
<img width="1920" height="1013" alt="image" src="https://github.com/user-attachments/assets/7e558bdf-b20f-4e44-958e-21b23eb88131" />

- Ở cột bên trái, bấm lại vào mục User Interface.

- Kéo thành phần Label (Nhãn chữ) thả vào bên trong cái khung VerticalArrangement vừa tạo.

- Nhìn sang cột Properties bên phải của Label1:

- Tìm thuộc tính Text (hiện đang là Text for Label1).

- Xóa chữ cũ đi và gõ vào: Họ và tên: Nguyễn Tuấn Anh.

- Làm tương tự, kéo thêm một cái Label nữa thả vào dưới cái cũ:

- Sửa thuộc tính Text của nó thành: Lớp: Kỹ thuật máy tính - 58KTP.
<img width="1920" height="1029" alt="image" src="https://github.com/user-attachments/assets/1e157143-1b08-4b0b-83ba-188fafeefcfc" />

- Ở cột User Interface bên trái, tìm thành phần Button (Nút bấm).

- Kéo Button thứ nhất thả vào dưới 2 cái Label:

- Nhìn sang cột bên phải, sửa thuộc tính Text thành: Giải Bài Toán.

- Nhìn xuống dưới một chút ở cột Components, bấm vào nút Rename (đổi tên component) và đổi thành Btn_ToanHoc để lát nữa qua phần code block không bị nhầm lẫn.

- Kéo tiếp Button thứ hai thả vào dưới nút thứ nhất:

- Sửa thuộc tính Text của nó thành: Xem Trang Web.

- Bấm Rename ở cột Components, đổi tên thành Btn_WebView.
<img width="1913" height="1022" alt="image" src="https://github.com/user-attachments/assets/d8e24b30-076b-426b-827a-e83a998ad0c6" />

- Vì ứng dụng của bạn cần 3 màn hình, nên bây giờ phải tạo sẵn khung cho Screen 2 và Screen 3:

- Nhìn lên thanh công cụ màu trắng ở phía trên (chỗ có chữ Screens: Screen1), sẽ thấy một nút có chữ Add Screen... (bên cạnh dấu cộng +).

- Bấm vào Add Screen...:

- Nó hiện ra bảng nhỏ, nhập tên màn hình thứ hai là: Screen_ToanHoc -> Bấm OK. (Chờ khoảng 3 giây màn hình sẽ chuyển sang trang trống mới).

- Sau khi nó load xong màn hình mới, nhìn lại thanh công cụ trên cùng, bấm vào chữ Screen_ToanHoc để chọn quay trở lại Screen1.

- Tiếp tục bấm Add Screen... một lần nữa:

- Nhập tên màn hình thứ ba là: Screen_WebView -> Bấm OK.
<img width="1277" height="896" alt="image" src="https://github.com/user-attachments/assets/e2ad2dc8-4000-44b1-b244-5158ea0f8b32" />

- bấm vào nút Blocks (ngay cạnh nút Designer). Màn hình sẽ chuyển sang một khoảng trắng lớn – đây là nơi ghép các khối lệnh.
<img width="1898" height="972" alt="image" src="https://github.com/user-attachments/assets/b7eb2632-d7de-4776-83b8-6a3bbbfc6025" />























