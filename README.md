# AUTOMATION TESTING PROJECT – GROUP 03

## 1. Giới thiệu

Dự án kiểm thử tự động các chức năng của hệ thống **Dolibarr ERP & CRM** trong khuôn khổ môn học Đảm bảo chất lượng và kiểm thử phần mềm.

- **Nhóm:** Group 03
- **Website kiểm thử:** https://demo.dolibarr.org/
- **Phiên bản Dolibarr:** 24.0.2 (phiên bản tại thời điểm kiểm thử)
- **Công cụ:** Katalon Recorder 7.1.0
- **Phương pháp:** Functional Testing (kiểm thử chức năng)
- **Phạm vi:** Các chức năng được phân công cho 5 thành viên trong nhóm

Các Automation Test Case tập trung kiểm tra thao tác CRUD (Create, Read, Update, Delete), dữ liệu đầu vào và các quy tắc nghiệp vụ.

## 2. Cấu trúc thư mục

- **Automation Testing Project - Group 03:** Chứa các Automation Script/Test Suite của thành viên.
- **Test Report - Group 03:** Chứa báo cáo kết quả kiểm thử và các file log thực thi.
- **Envidence - Group03:** Chứa ảnh chụp màn hình và minh chứng quá trình chạy automation.
- **README.md:** Hướng dẫn cài đặt, cấu hình và thực thi project.

Các script được đặt tên theo chức năng để thuận tiện cho việc quản lý và tích hợp.

## 3. Yêu cầu môi trường

- Máy tính có kết nối Internet.
- Trình duyệt Google Chrome.
- Extension Katalon Recorder 7.1.0.
- Quyền truy cập hệ thống Dolibarr Demo và các module cần kiểm thử.

**Lưu ý:** Dự án sử dụng Katalon Recorder dưới dạng extension trình duyệt, không yêu cầu tự xây dựng backend hoặc cài đặt Katalon Studio.

## 4. Hướng dẫn chạy Automation Test

### Bước 1: Tải project

Clone repository GitHub của nhóm hoặc chọn **Code → Download ZIP**, sau đó giải nén.

### Bước 2: Cài đặt Katalon Recorder

1. Mở Google Chrome.
2. Cài đặt extension Katalon Recorder.
3. Mở Katalon Recorder và chuẩn bị trình duyệt để thực thi.

### Bước 3: Import Automation Script

1. Trong Katalon Recorder, sử dụng chức năng **Open Test Suite/Import**.
2. Chọn file Test Suite đã xuất từ Katalon Recorder trong thư mục `Automation Testing Project - Group 03`.
3. Import các Test Suite cần thiết.
4. Kiểm tra danh sách Test Case sau khi import.

### Bước 4: Chuẩn bị môi trường kiểm thử

1. Truy cập https://demo.dolibarr.org/.
2. Đăng nhập nếu hệ thống yêu cầu.
3. Đảm bảo các module liên quan đã được kích hoạt.
4. Kiểm tra quyền truy cập và dữ liệu tiền điều kiện của từng Test Case.
5. Đảm bảo các dữ liệu thử nghiệm không xung đột với nhau.

### Bước 5: Thực thi Automation Test

Katalon Recorder cung cấp ba chế độ thực thi:

- **Play Test Case:** Chạy một Test Case được chọn.
- **Play Test Suite:** Chạy toàn bộ Test Case trong một Test Suite.
- **Play All Suites:** Chạy tất cả Test Suite đã import.

Khuyến nghị chạy riêng từng Test Suite để kiểm tra trước, sau đó chạy toàn bộ các suite để thực hiện kiểm thử tích hợp.

## 5. Kết quả kiểm thử

Sau khi chạy, kiểm tra trạng thái các Test Case và log trong Katalon Recorder.

Các trạng thái được sử dụng trong báo cáo:

- **Passed:** Kết quả thực tế đáp ứng kết quả mong đợi.
- **Failed:** Kết quả thực tế khác kết quả mong đợi.
- **Blocked:** Không thể hoàn thành kiểm thử do điều kiện cản trở.
- **Skipped:** Test Case được bỏ qua.
- **Untested:** Test Case chưa được thực thi.

Kết quả tổng hợp, thời gian thực thi và danh sách các Test Case không đạt được lưu tại thư mục `Test Report - Group 03`.

Ảnh chụp màn hình minh chứng quá trình chạy kiểm thử được lưu tại `Envidence - Group03`.

## 6. Lưu ý khi thực thi

- Website Dolibarr Demo là môi trường trực tuyến; dữ liệu và cấu hình có thể thay đổi.
- Một số Test Case yêu cầu chuẩn bị dữ liệu trước khi chạy.
- Các script sử dụng ID, URL hoặc XPath cố định có thể cần được kiểm tra khi môi trường thay đổi.
- Không chỉnh sửa hoặc xóa dữ liệu của người dùng khác.
- Nếu Test Case thất bại, cần đối chiếu Expected Result, Actual Result và log để xác định nguyên nhân.
- Nên chạy lại các trường hợp thất bại để kiểm tra tính ổn định của Automation Script.

## 7. Tài liệu tham khảo

- Dolibarr Demo: https://demo.dolibarr.org/
- Katalon Recorder: https://katalon.com/
- GitHub repository: https://github.com/CrisDoDev/Group03_Dolibarr.git

---

**Group 03 – Software Quality Assurance & Testing**