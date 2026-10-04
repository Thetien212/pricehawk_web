<div align="center">

# 🦅 PriceHawk

**Theo dõi giá thông minh – xem lịch sử giá trước khi mua.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chartdotjs&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

[🌐 Xem demo](https://Thetien212.github.io/pricehawk/) · [🐛 Báo lỗi](https://github.com/Thetien212/pricehawk/issues) · [💡 Đề xuất tính năng](https://github.com/Thetien212/pricehawk/issues)

</div>

---

## 📖 Giới thiệu

PriceHawk là ứng dụng web một trang giúp người dùng tìm sản phẩm, xem **biểu đồ lịch sử giá**, lưu sản phẩm vào danh sách theo dõi và cài đặt cảnh báo khi giá giảm. Mục tiêu là giúp quyết định mua hàng đúng thời điểm, tránh bị "giảm giá ảo".

> ⚠️ **Đây là bản demo học tập.** Dữ liệu sản phẩm là dữ liệu mẫu. Tài khoản chỉ được lưu trong `localStorage` của trình duyệt, không có máy chủ hay cơ sở dữ liệu thật phía sau.

## 🖼️ Ảnh chụp màn hình

<!-- Chụp màn hình, bỏ vào thư mục docs/ rồi bỏ comment các dòng dưới -->
<!--
| Trang chủ | Chi tiết sản phẩm |
|-----------|-------------------|
| ![Trang chủ](docs/home.png) | ![Chi tiết](docs/detail.png) |
-->

## ✨ Tính năng

- 🔍 Tìm kiếm và lọc sản phẩm
- 📈 Biểu đồ lịch sử giá trên trang chi tiết sản phẩm
- ⭐ Danh sách theo dõi (watchlist)
- 🔔 Cài đặt cảnh báo giá
- 📊 Bảng điều khiển (dashboard) tổng quan
- 👤 Đăng ký / đăng nhập giả lập và trang hồ sơ cá nhân
- 🌗 Giao diện sáng / tối, tự nhận theo hệ thống
- 📱 Responsive, dùng tốt trên điện thoại

## 🛠️ Công nghệ

| Thành phần | Chi tiết |
|------------|----------|
| Giao diện | HTML, CSS, JavaScript thuần (một file `index.html`) |
| Biểu đồ | [Chart.js 4.4.1](https://www.chartjs.org/) qua CDN |
| Font | Space Grotesk, IBM Plex Sans, IBM Plex Mono (Google Fonts) |
| Lưu trữ | `localStorage` của trình duyệt |

## 🚀 Bắt đầu

### Cách 1: Mở trực tiếp

Tải repo về và mở file `index.html` bằng trình duyệt.

### Cách 2: Chạy server cục bộ

```bash
git clone https://github.com/Thetien212/pricehawk.git
cd pricehawk
python -m http.server 8000
```

Sau đó mở http://localhost:8000.

> Cần có kết nối Internet để tải Chart.js, font và ảnh sản phẩm.

## 🔑 Tài khoản demo

| Email | Mật khẩu |
|-------|----------|
| `demo@pricehawk.vn` | `demo1234` |

## 📁 Cấu trúc thư mục

```
pricehawk/
├── index.html     # Toàn bộ ứng dụng (HTML + CSS + JS)
├── README.md      # Tài liệu dự án
├── LICENSE        # Giấy phép MIT
└── .gitignore
```

## 🌍 Triển khai lên GitHub Pages

1. Vào **Settings → Pages**
2. Source: **Deploy from a branch**, chọn nhánh `main`, thư mục `/ (root)`
3. Bấm **Save**, chờ 1–2 phút rồi truy cập `https://Thetien212.github.io/pricehawk/`

## ⚠️ Hạn chế đã biết

- Ảnh sản phẩm được nhúng từ các trang bên thứ ba (Shopee, Lazada, Cellphones...). Nếu link hỏng, ảnh sẽ không hiện.
- Cơ chế băm mật khẩu chỉ để minh họa, **không an toàn cho môi trường thật**.
- Giá và lịch sử giá là dữ liệu mô phỏng, chưa lấy từ sàn thương mại điện tử thật.

## 🗺️ Lộ trình

- [ ] Tách `index.html` thành `style.css` và `app.js`
- [ ] Lưu ảnh sản phẩm cục bộ trong `images/`
- [ ] Kết nối backend và cơ sở dữ liệu thật
- [ ] Thu thập giá thật từ các sàn thương mại điện tử
- [ ] Gửi cảnh báo giá qua email / thông báo đẩy

## 🤝 Đóng góp

Mọi đóng góp đều được chào đón.

1. Fork repo
2. Tạo nhánh mới: `git checkout -b feature/ten-tinh-nang`
3. Commit: `git commit -m "Thêm tính năng X"`
4. Push: `git push origin feature/ten-tinh-nang`
5. Mở Pull Request

## 📄 Giấy phép

Phân phối theo giấy phép MIT. Xem file [LICENSE](LICENSE) để biết thêm chi tiết.

## 👤 Tác giả

**Thetien212** – [@Thetien212](https://github.com/Thetien212)
