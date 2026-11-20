# Token trích từ Figma "CRM Dashboard (Community)"

Nguồn: https://www.figma.com/design/5ohudTALDaMR3p2n4fmslG (bản duplicate từ Community; file ghi rõ là bản mô phỏng một shot Dribbble).
Trích ngày 19/11/2026 bằng Figma MCP (get_variable_defs, get_metadata, get_screenshot).

## Màu
| Token | Giá trị | Dùng cho |
|---|---|---|
| Colors/Primary/300 | #4D4AEA | Nút chính, link, tab đang chọn, nav đang chọn |
| Colors/Primary/200 | #DFDEFF | Viền/nền nhấn nhẹ |
| Colors/Primary/100 | #F4F3FF | Nền nav đang chọn, nút secondary, filter chip |
| Colors/Base/Black | #2A2A2A | Chữ chính |
| Colors/Base/White | #FFFFFF | Nền |
| Colors/Gray/400 | #57595B | Chữ phụ |
| Colors/Gray/300 | #8C8E90 | Chữ mờ (⚠ chỉ ~3.3:1 trên nền trắng, không đạt AA cho chữ thường) |
| Colors/Gray/200 | #ECECEE | Đường kẻ, track progress |
| Colors/Gray/100 | #F9F9FD | Nền header bảng |
| Gray/300 (foundation) | #D8D9DD | Viền input/nút |
| Gray/600 | #475467 | Chữ phụ đạt AA |
| Gray/1000 | #2D2E33 | Chữ đậm |
| Colors/Success/100 | #EAFDEE | Nền chip "Customer" |
| Colors/Success/200 | #147129 | Chữ chip "Customer" |
| Shadow | 0 2px 4px #0000000D | Thẻ, nút |

## Chữ (Inter, Medium là chủ đạo)
| Token | Cỡ / dòng | Weight |
|---|---|---|
| Title/Lg | 36 / 46, letter-spacing −1 | 500 |
| Title/Md | 28 / 38 | 500 |
| Body/Large | 16 / 20 | 500 |
| Text md/Regular | 16 / 24 | 400 |
| Body/Medium | 14 / 18 | 500 |
| Body/Sm | 12 / 16 | 500 |
| Body/Sm 2.0 | 12 / 18 | 500 |

## Component có trong file
Nav Base (Default / Focused, có badge đếm), Button (Primary / Gray / Secondary), Chip (Churned / Customer),
Card (số liệu + badge tăng trưởng), Table Header Cell, Table Cell (logo + checkbox, chip, avatar group,
text, progress bar, icon), Section tab (Active / Hidden), Checkbox (6 trạng thái), Avatar, Avatar Group,
Progress (10–80%), bộ icon 24px nét mảnh.

## Bố cục mẫu
Sidebar sáng 341px (logo, 6 mục nav, 3 mục dưới, thẻ người dùng) · nội dung: tiêu đề + 2 nút ·
tab ngang gạch chân · 3 thẻ KPI · filter chip + ô tìm · bảng có checkbox · phân trang.
Bo góc ~8px, chiều cao control 40px, dòng bảng 76px.
