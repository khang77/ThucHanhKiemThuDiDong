#### Thực hành kiểm thử di động - Thiết bị Android  
### ỨNG DỤNG ĐẶT ĐỒ UỐNG ONLINE

##### 📁 Tài liệu đặc tả kỹ thuật SRS:

[SRS_Chức năng - nghiệp vụ của hệ thống ứng dụng đặt đồ uống (order drink).docx](https://github.com/khang77/ThucHanhKiemThuDiDong_Testcase_Android/files/12346875/SRS_Ch.c.nang.-.nghi.p.v.c.a.h.th.ng.ng.d.ng.d.t.d.u.ng.order.drink.docx)

##### 🌻 Giải thích về hệ thống:

Ý nghĩa, mục đích: 
- Quản lý việc đặt đồ uống dễ dàng hơn, giúp cho chủ cửa hàng quản lý số lượng đơn hàng chính xác.
- Theo dõi doanh thu ngay trên điện thoại thông minh hoặc máy tính bảng.
- Hỗ trợ khách đặt đồ uống bằng ứng dụng
  
##### ✴️ Đối tượng tham gia vào hệ thống: 
- Admin (là người quản trị hệ thống, có thể là chủ cửa hàng, nhân viên ...)
- Customer (khách hàng đặt đồ uống tại chỗ hoặc mang về)

##### 🔯 Các chức năng chính của hệ thống: 
- 🔘 Đăng ký
- ✔️ Đăng nhập
- ❌ Đăng xuất
##### Customer
- Xem Menu
- Xem đồ uống
- Xem giỏ hàng
- Thêm, sửa, xóa đồ uống
- Thanh toán
- Xem hóa đơn
- Xem lịch sử đặt đồ
##### Admin
- Quản trị tài khoản
- Quản lý đồ uống
- Thống kê doanh thu
- Quản trị hóa đơn
- Quản lý Order

##### ⏯️ Các bước thực hiện:

1. Đọc, hiểu, phân tích chức năng và nghiệp vụ hệ thống, phần mềm thông qua tài liệu đặc tả kỹ thuật SRS được cung cấp.
2. Viết bộ testcase cho ứng dụng dựa trên các chức năng, nghiệp vụ được định nghĩa trong SRS.
3. Cài đặt ứng dụng trên Android Studio (setting mô phỏng 2 thiết bị có kích thước khác nhau: Pixel_XL(5.5") & Nexus7(7"))
4. Thực hiện kiểm thử dựa trên các testcase đã viết và báo cáo kết quả trên file.
    - Kiểm thử giao diện, thành phần
    - Kiểm thử chức năng
    - Kiểm thử luồng nghiệp vụ
5. Với các testcase failed, thực hiện log bug trên file excel.
6. Đề xuất cải tiến chức năng của app

***
![flow](https://github.com/khang77/ThucHanhKiemThuDiDong_Testcase_Android/assets/92577611/22b664ff-e570-43b5-a08a-d711bd42026b)


![flow2 drawio](https://github.com/khang77/ThucHanhKiemThuDiDong_Testcase_Android/assets/92577611/9d19ff94-016f-4094-b18c-758306028643)

***

|💡 Đề xuất cải tiến chức năng của app 💡 |
|---|
|🉑 Chức năng cho phép nhập thẳng số vào ô số lượng |
|Khi khách có mong muốn đặt số lượng nhiều, việc phải nhấn '+' liên tục rất khó khăn. Nên có tính năng nhập thẳng con số mong muốn sẽ tối ưu trải nghiệm người dùng|
|🔍 Chức năng tìm kiếm món |
|Giúp khách lọc danh sách và tiếp cận nhanh món mình mong muốn, tăng sự hài lòng |
|㊙️ Chức năng Mã hóa kí tự Password khi thực hiện đăng ký tài khoản |
|Khi nhập Password cần mã hóa các ký tự để bảo mật thông tin| |

##### TestCase & DefectLog
![asm2_testcase](https://github.com/khang77/ThucHanhKiemThuDiDong_Testcase_Android/assets/92577611/9512e9f3-9ae1-40ac-b722-9da96ed73dd8)

![asm2_defectlog](https://github.com/khang77/ThucHanhKiemThuDiDong_Testcase_Android/assets/92577611/7521231c-b2dd-4d74-b133-24115cf89a16)

![android_studio](https://github.com/khang77/ThucHanhKiemThuDiDong_Testcase_Android/assets/92577611/1ea17d00-975c-448b-9f18-7c97a0158fb5)

![chart](https://github.com/khang77/ThucHanhKiemThuDiDong/assets/92577611/f9577566-141e-48bf-b0bb-6f001f1d5893)


