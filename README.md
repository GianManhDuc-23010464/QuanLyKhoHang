# Hướng dẫn cài đặt và sử dụng hệ thống quản lý kho hàng

### Chạy file JAR

**Lưu ý**: Bạn cần cài đặt **OpenJDK Platform** để khởi chạy ứng dụng.

### Cách cài đặt OpenJDK Platform (dành cho Windows):

1. Mở **Command Prompt**.
2. Nhập lệnh sau để cài đặt **Oracle Java Runtime Environment**:

   ```bash
   winget install Oracle.JavaRuntimeEnvironment
   ```

   Nhấn **Y** để xác nhận cài đặt.

3. Sau khi hệ thống hiện thông báo **install successfully**, nhập tiếp lệnh sau:
   ```bash
   winget install Oracle.JDK.23
   ```
4. Sau khi tải về, hệ thống sẽ tự động bắt đầu cài đặt. **Lưu ý**: Khi cài đặt, sẽ có các pop-up yêu cầu xác nhận. Hãy đồng ý để tiếp tục cài đặt.

5. Khi cài đặt hoàn tất và màn hình hiện thông báo **install successfully**, bạn cần **khởi động lại máy tính**.

6. Sau khi khởi động lại, bạn có thể chạy file JAR với **OpenJDK Platform**.

7. Tiến hành sử dụng phần mềm.

---

### Đăng nhập hệ thống

1.  Đăng nhập hệ thống :
    mặc định với tài khoản :

- tài khoản : "admin"
- mật khẩu :"admin"

2.  Sau khi đăng nhập sẽ được điều hướng tới Khởi động app :
    click : " Start "
3.  Sau khi click : " Start " sẽ được điều hướng tới màn hình chính :
    Màn hình quản lý kho hàng :

- ở đây sẽ hiển thị danh sách hàng hóa
- có những button lựa chọn : + "Thêm" // Để thêm những mặt hàng + "Xuất" // Để xuất mặt hàng mình muốn + "Logout"// Để thoát khỏi app + "Quay Lại"// Để quay trở ề giao diện khởi động app + Những tính năng khác đang được phát triển thêm

4. Giao diện Thêm và Xuất

(1). Giao diện thêm :

- sau khi click vào button "Thêm " thì vào giao diện Thêm mặt hàng
- ở đây có nhứng thông tin mặt hàng cần điền : + Mã hóa đơn : là mã của mặt hàng cần thêm + Tên hàng : là tên của mặt hàng + Số Lượng : là số lượng của mặt hàng đấy + Giá : là tổng giá trị của mặt hàng tính bằng VNđ + HSD : là hạn sử dụng của mặt hàng + Nhà cung cấp : là nhà cung cấp mặt hàng

- button "Thêm " là để thêm mặt hàng vào danh sách
- button "thoát" là để quay trở về giao diện quản lý kho

(2). Giao diện xuất

- sau khi click vào button "Xuất " thì vào giao diện Xuát mặt hàng
- ở đây có thông tin mặt hàng cần xuất kho : + Mã hàng : mã của mặt hàng + số lượng xuất : là số lượng mặt hàng cần xuát
- button "xuất" là để xuất mặt hàng
- button "thoát" là để quay trở về giao diện quản lý kho

## Lưu Ý :

- đây là bản demo , nên chưa có đầy đủ tính năng , đang trong giai đoạn phát triển thêm.
- Thầy cô và các bạn xem , xin hãy cho nhận xét về phần mềm này .
