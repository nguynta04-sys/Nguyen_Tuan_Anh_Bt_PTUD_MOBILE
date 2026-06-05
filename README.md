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

- giao diện cho màn hình Screen_ToanHoc
- Nhìn sang cột Properties bên phải ngoài cùng, tìm thuộc tính AlignHorizontal và đổi nó từ Left : 1 thành Center : 3 (để lát nữa các ô nhập số tự động căn giữa).
<img width="1920" height="1029" alt="image" src="https://github.com/user-attachments/assets/bb837708-972b-4c21-887c-bab529820782" />

- Kéo một cái Label (Nhãn chữ) vào:

- Nhìn sang cột Properties bên phải, tìm ô Text, xóa chữ cũ đi và gõ: Nhập một số nguyên bất kỳ:
<img width="1920" height="995" alt="image" src="https://github.com/user-attachments/assets/554c691b-9de1-4054-b917-00b8c87e1333" />

- Kéo một cái TextBox (Ô nhập dữ liệu) thả vào phía dưới cái Label:

- Nhìn sang cột Properties bên phải, tích chọn vào ô NumbersOnly (để ép người dùng chỉ được nhập số, không nhập được chữ).

- Nhìn xuống cột Components (cột thứ 3), bấm vào nút Rename ở dưới và đổi tên nó thành Txt_NhapSo.
<img width="1920" height="937" alt="image" src="https://github.com/user-attachments/assets/3c43ef27-1949-48c9-8960-6ec7914c3c19" />

- Kéo một cái Button (Nút bấm) thả vào phía dưới ô TextBox:

- Nhìn sang cột Properties bên phải, tìm ô Text và sửa thành chữ: Kiểm tra số

- Nhìn xuống cột Components, bấm nút Rename và đổi tên nó thành Btn_KiemTra.
<img width="1920" height="1037" alt="image" src="https://github.com/user-attachments/assets/f30d9a60-2282-44c2-92ce-888e6ce72427" />

- Kéo thêm một cái Label nữa thả xuống dưới cùng để hiển thị kết quả:

- Nhìn sang cột Properties, tìm ô Text và sửa thành: Kết quả sẽ hiển thị tại đây

- Bạn có thể đổi màu chữ ở mục TextColor thành màu Đỏ (Red) hoặc Xanh để nhìn cho rõ.

- Nhìn xuống cột Components, bấm nút Rename và đổi tên nó thành Lbl_KetQua.
<img width="1885" height="1073" alt="image" src="https://github.com/user-attachments/assets/bf045edf-8e5a-4ecb-af70-8e221146c406" />

- Kéo thêm một cái Button cuối cùng để làm nút quay lại:

- Nhìn sang cột Properties, sửa Text thành: Quay lại Trang chủ

- Bấm nút Rename ở cột Components và đổi tên thành Btn_QuayVe.
<img width="1917" height="963" alt="image" src="https://github.com/user-attachments/assets/41aac0cb-dce1-47f1-958b-064e27508a63" />

- ảnh dưới là kết quả của block Btn_KiemTra và Btn_QuayVe
<img width="1920" height="910" alt="image" src="https://github.com/user-attachments/assets/b7e4c84e-81ac-48bd-9afd-d89ca75ef51e" />

- tiếp tục với block Screen_WebView
<img width="1912" height="895" alt="image" src="https://github.com/user-attachments/assets/335b9c8d-b241-4a71-a3ac-7d4afb41a4d4" />

- Chuyển sang màn hình Screen_WebView và vào giao diện Designer
<img width="1920" height="1036" alt="image" src="https://github.com/user-attachments/assets/e90e1e3e-dab2-4252-8e0f-2ec0cc4aba14" />

- Ở cột User Interface ngoài cùng bên trái, cuộn xuống gần dưới cùng tìm thành phần tên là WebViewer 

- Kéo cái WebViewer đó thả vào trong màn hình điện thoại ảo ở giữa.

- Nhìn sang cột thuộc tính Properties bên phải ngoài cùng của cái WebViewer1 vừa kéo vào:

- Tìm thuộc tính HomeUrl: copy và dán chính xác đường link được yêu cầu trong đề bài vào đây: https://tinhte.vn
<img width="1920" height="1021" alt="image" src="https://github.com/user-attachments/assets/43161b64-ff01-44fa-9ec4-0d1f264b7b1d" />

- Để người dùng không bị "kẹt" lại ở màn hình xem web, nên làm thêm một nút nhỏ ở trên đầu để quay về.

- Kéo một cái Button từ cột bên trái thả vào màn hình.

- Sửa thuộc tính Text của nút đó thành: Quay lại Trang chủ.

- Đổi tên nút ở cột Components (Rename) thành: Btn_QuayVeWeb.
<img width="1920" height="1049" alt="image" src="https://github.com/user-attachments/assets/65abcff8-c796-4514-a4c0-3b74e161e3bd" />

- Bây giờ, bấm sang nút Blocks ở góc trên cùng bên phải để lập trình cho nút quay về:

- Nhìn cột danh sách bên trái dưới mục Screen_WebView, bấm vào nút Btn_QuayVeWeb. Kéo khối lệnh when Btn_QuayVeWeb.Click do thả ra khoảng trống.

- Bấm vào mục Control (khối màu vàng đậm) bên trái, kéo khối open another screen with screen name lắp vào trong.
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/5ada0207-b7bf-44ce-9c88-50ca0363d2c8" />

- dưới đây là kết quả của MIT app khi connect sucsess
<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/cfdf5856-8cd2-485d-9d15-f020aafe9ee5" />
<img width="1280" height="960" alt="image" src="https://github.com/user-attachments/assets/98482974-2d24-4049-acae-b5c9e8006fdb" />














