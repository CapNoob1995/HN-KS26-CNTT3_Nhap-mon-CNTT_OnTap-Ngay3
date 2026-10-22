# Steam Game Hub



## Giới thiệu

Đây là hệ thống quản lý và tra cứu thông tin trò chơi trực tuyến. Dự án **tập trung tối ưu hóa** *trải nghiệm tìm kiếm* và phân loại game cho cộng đồng game thủ trên nền tảng Steam.



## Cấu trúc thư mục dự án

Dưới đây là bảng mô tả chi tiết các phân vùng chính trong hệ thống:



| Thư mục | Nội dung |

| :--- | :--- |

| `docs` | Lưu trữ tài liệu hướng dẫn và báo cáo kỹ thuật |

| `media` | Chứa hình ảnh poster, trailer và asset giao diện game |

| `data` | Lưu trữ cơ sở dữ liệu game, file Excel thống kê người chơi |



## Quy trình đăng ký tài khoản chơi game tại TTA

1. Truy cập vào trang chủ quản lý dịch vụ game Steam Hub.

2. Điền thông tin cá nhân và chọn gói trò chơi mong muốn.

3. Xác nhận qua email và nhận mã kích hoạt tài khoản.



## Lệnh kiểm tra hệ thống (CLI)

Sử dụng câu lệnh sau trên PowerShell hoặc Terminal để liệt kê toàn bộ cấu trúc dự án:

```powershell

Get-ChildItem -Recurse -Force

