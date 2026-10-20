# HCM-KS26-CNTT2_Nhap-mon-CNTT_Session2_Ex3
**PHẦN 1: PHÂN TÍCH VÀ ĐỀ XUẤT GIẢI PHÁP**

**1. Tình trạng máy và Swap/Page File:**

Tình trạng: Mở 30 tab Chrome làm tràn 98% RAM, gây nghẽn hệ thống.

Swap/Page File: Windows tự động lấy ổ cứng làm bộ nhớ ảo khi RAM vật lý đầy.

HDD vs SSD NVMe:

Với HDD: Đọc/ghi chậm nên bị nghẽn 100% Disk, gây đơ chuột và giật lag nặng.

Với SSD NVMe: Tốc độ rất nhanh nên máy chỉ giảm hiệu năng nhẹ, không bị đơ cứng.

**2. Luồng IPO của 1 tab Chrome:**

Input: Nhập URL, click chuột, gõ phím.

Process: CPU xử lý mã nguồn và dựng giao diện.

Output: Hiển thị hình ảnh/giao diện lên màn hình.

Vị trí dữ liệu: Tab đang chạy nằm trên RAM; các tab bị tràn RAM đẩy xuống Storage (ổ cứng).

**3. 3 hành động giải phóng RAM lập tức:**

Tắt bớt tab chưa dùng hoặc bật tính năng Memory Saver trong Chrome.

Mở Task Manager -> Chọn Chrome chiếm nhiều RAM -> Bấm End Task.

Nhấn Shift + Esc ngay trong Chrome để tắt trực tiếp các tab nặng.

PHẦN 2: BÁO CÁO CHẨN ĐOÁN (TASK MANAGER)

Thông số: %CPU: 45% (Bình thường) | %RAM: 98% (Quá tải) | %Disk: 100% (Nghẽn nặng).

Nguyên nhân: RAM quá tải buộc Windows dùng HDD làm bộ nhớ ảo, kéo theo HDD bị nghẽn 100%.

Khuyến nghị: Tắt bớt tab ngầm ngay (trước mắt); nâng cấp lên SSD NVMe và gắn thêm RAM (lâu dài).
