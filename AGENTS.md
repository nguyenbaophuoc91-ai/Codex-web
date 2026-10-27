# AGENTS.md

## Dự án
- Đây là dự án giới thiệu và tư vấn SIM/gói cước MobiFone; trao đổi và nội dung ưu tiên bằng tiếng Việt.
- `Số đẹp.xlsx` là nguồn dữ liệu danh mục SIM. Giữ số điện thoại ở dạng văn bản để bảo toàn số 0 đầu; không tự bịa số hoặc giá để lấp dữ liệu trống.
- `Website-MobiFone-ban-gui-sep.html` và `Website-MobiFone-ban-gui-sep.zip` là bản xuất để xem/gửi, không mặc định là nguồn mã chuẩn. Sau khi sửa website, cập nhật bản xuất từ đúng nguồn Site.

## Khi sửa website
- Site đang dùng project ID `appgprj_6adcca1cfba88191af09f989c6a18092`. Ưu tiên quy trình và công cụ Sites để chỉnh sửa, đóng gói và triển khai; không tạo Site mới.
- Giữ nguyên chế độ truy cập hiện tại. Chỉ thay đổi quyền truy cập khi người dùng yêu cầu rõ ràng.
- Danh sách SIM phải giữ đủ dữ liệu từ bảng Excel, có thể tìm kiếm/lọc/phân trang và không làm mất số 0 đầu.
- Biểu mẫu luận phong thủy cần nhận số SIM, ngày sinh và giờ sinh, sau đó hiện kết quả cụ thể theo thông tin nhập: mức tương hợp, luận giải các khía cạnh và gợi ý số trong kho.
- Nêu rõ quy ước tính phong thủy chỉ mang tính văn hóa/tham khảo; không khẳng định dự báo vận mệnh. Không chẩn đoán hay dự báo sức khỏe.
- Giữ các liên kết Zalo, hướng dẫn kích hoạt, gói cước và địa chỉ liên hệ hiện có trừ khi người dùng yêu cầu đổi.

## Quy trình
- Trước khi sửa, xác định đúng nguồn mã đang triển khai và kiểm tra dữ liệu Excel liên quan.
- Sau khi sửa, kiểm tra cú pháp/chức năng phù hợp, cập nhật bản HTML/ZIP xuất nếu thay đổi ảnh hưởng đến website, rồi triển khai theo đúng audience hiện có.
- Không đưa thông tin cá nhân, dữ liệu đăng nhập hoặc token vào mã nguồn hay commit.
