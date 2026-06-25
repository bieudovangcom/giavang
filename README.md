# GitHub Pages Static Build - Biểu Đồ Vàng / Giá Vàng

Bộ code tĩnh đã được làm sạch để upload trực tiếp lên GitHub Pages.

## Cách dùng
1. Upload `index.html` lên root repo GitHub Pages.
2. Vào Settings → Pages → Deploy from branch.
3. Chọn branch `main` và thư mục `/root`.

## Đã fix
- Xóa Cloudflare Rocket Loader / beacon / email decode không chạy trên GitHub Pages.
- Chuyển script type bị mã hóa về `text/javascript`.
- Chuẩn hóa ảnh lazyload `data-src` thành `src` để ảnh hiển thị ngay.
- Chuyển link tương đối thành link tuyệt đối về `https://bieudovang.com/`.
- Thêm JS fallback cho mobile menu, submenu, filter bảng giá và biểu đồ tĩnh.
- Giữ SEO meta, canonical, Open Graph, Twitter card và JSON-LD schema.
