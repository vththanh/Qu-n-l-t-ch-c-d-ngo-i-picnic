# Tên đề tài: Quản lý tổ chức dã ngoại, picnic
Môn: Phân tích và thiết kế hệ thống 
## Mô tả dự án:
- Dự án xác định rõ vai trò các bộ phận, cung cấp dịch vụ dã ngoại/picnic: đặt lịch, quản lý dịch vụ, quản lý kho, thanh toán và xử lý sự cố.
- Thu thập và chuẩn hóa yêu cầu từ: Khách hàng,bộ phận Kinh doanh, Dịch vụ, Kho, Hậu cần, Kế toán.
- Xây dựng BPC, DFD (mức ngữ cảnh, mức 0, mức 1) để mô tả luồng dữ liệu và phân rã chức năng.
- Thiết kế ERD, mô hình dữ liệu quan hệ, đảm bảo ràng buộc toàn vẹn.
- Biểu mẫu nghiệp vụ: Đơn hàng, Hóa đơn, Phiếu mua/nhập, Biên bản giải quyết sự cố.
- Xác định Business Rules (quy định đặt cọc, hủy dịch vụ, phụ thu) và Business Requirements (BRD).
- Thiết kế giao diện người dùng (UI).
## Mục tiêu dự án 
- Số hóa quy trình đặt lịch và đơn hàng, giảm thao tác thủ công của lễ tân.
- Kiểm soát kho (thực phẩm, dụng cụ) theo phiếu mua/nhập, hạn chế thiếu/ dư tồn.
- Tự động hóa lập hóa đơn và chuẩn hóa quy định thanh toán, phụ thu.
- Chuẩn hóa quy trình xử lý khiếu nại.
## Quy trình nghiệp vụ chính 
- Đặt lịch trên website → hệ thống tự cập nhật lịch hẹn.
- Đặt cọc và xác nhận.
- Lập đơn hàng và check-in.
- Ghi nhận phát sinh.
- Quản lý kho: lập phiếu mua hàng → duyệt (Kinh doanh) → phiếu nhập.
- Check-out và lập hóa đơn (bao gồm phát sinh).
- Giải quyết khiếu nại: lập biên bản và lưu trữ.
