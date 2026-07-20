# WEBSITE CÔNG TY TNHH ĐẦU TƯ LAVALAND

Website tĩnh responsive, không cần framework hoặc quy trình build.

## Triển khai nhanh

**Phương án tối ưu chi phí: Netlify**

1. Đăng nhập Netlify → Add new site → Deploy manually.
2. Kéo toàn bộ thư mục này hoặc file ZIP vào vùng tải lên.
3. Website được cấp địa chỉ tạm thời; biểu mẫu tư vấn được ghi nhận tại mục Forms.
4. Kết nối tên miền riêng trong Domain management.

Xem thử tại máy tính bằng lệnh:

```bash
python3 -m http.server 8000
```

Sau đó mở `http://localhost:8000`.

## Thành phần đã hoàn thiện

- Trang giới thiệu LAV, năng lực, dự án, công cụ tài chính và liên hệ.
- Nhận diện thương hiệu theo hệ màu Teal Green, Sandy Gold, Ivory White, Charcoal Navy và font Montserrat.
- Dự án Vega Homes Quang Châu và phối cảnh Thiên Ân Center.
- Tính tiến độ thanh toán CT.01 và khoản vay dự kiến.
- Netlify Forms, trang cảm ơn, chống spam, chính sách bảo mật.
- SEO cơ bản, dữ liệu có cấu trúc, PWA/offline cache và cấu hình bảo mật hosting.

## Dữ liệu còn thiếu trước khi công bố chính thức

| Hạng mục | Người phụ trách đề xuất | Thời hạn |
|---|---|---|
| Tên miền chính thức | Ban Giám đốc / IT | Trước quảng cáo |
| Email doanh nghiệp và email nhận lead | HCNS / IT | Trước công bố |
| Facebook, Zalo OA, YouTube | Marketing | Trước chiến dịch |
| GA4 / Meta Pixel | Marketing | Trước chạy quảng cáo |
| Xác nhận chính sách, pháp lý dự án còn hiệu lực | Pháp chế / Kinh doanh | Trước mỗi đợt bán |
| Ảnh văn phòng, nhân sự, hoạt động thực tế | Marketing / HCNS | 03–05 ngày |

## KPI đề xuất 30 ngày đầu

| KPI | Mục tiêu |
|---|---:|
| Thời gian tải trang trên 4G | ≤ 3 giây |
| Tỷ lệ nhấp gọi điện / mở biểu mẫu | ≥ 5% phiên |
| Tỷ lệ gửi biểu mẫu | ≥ 2% phiên |
| Thời gian phản hồi lead trong giờ làm việc | ≤ 5 phút |
| Tỷ lệ lead đủ điều kiện | ≥ 25% |

## Vị trí chỉnh sửa

- Nội dung và số điện thoại: `index.html`
- Màu sắc, bố cục: `assets/css/styles.css`
- Công thức và tương tác: `assets/js/app.js`
- Hình ảnh: `assets/img/`

**Lưu ý:** công cụ tài chính chỉ là ước tính. Kinh phí bảo trì, lãi suất sau ưu đãi và điều kiện tín dụng phải căn cứ hợp đồng/văn bản chính thức.
