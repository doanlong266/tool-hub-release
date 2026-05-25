# Tool Hub Release

Tool Hub Release là repo giới thiệu bản public của ToolHub. Repo này chỉ giữ README để mô tả tính năng, link triển khai và nguồn chính của sản phẩm.

## Link public

- Vercel Production: https://tool-hub.vercel.app

> Ghi chú: `toolhub.vercel.app` đang thuộc một deployment khác, nên bản public hiện dùng domain `tool-hub.vercel.app`.

## ToolHub là gì?

ToolHub là dashboard web tổng hợp các công cụ theo dõi dữ liệu thị trường. Phiên bản hiện tại tập trung vào nhóm giá hàng hóa và tỷ giá, thiết kế theo dạng dashboard hiện đại, có sidebar theo danh mục và hỗ trợ tiếng Việt/tiếng Anh.

## Tính năng chính

- Màn hình chào có lời chào theo buổi và câu gợi ý công cụ.
- Chuyển ngôn ngữ Việt/Anh bằng menu cờ.
- Sidebar `Giá` với các danh mục: Xăng & Dầu, Vàng, Bạc, Tỷ giá.
- Bảng giá xăng dầu lấy dữ liệu từ Petrolimex.
- Bảng giá vàng lấy dữ liệu từ Vang Today.
- Bảng giá bạc lấy dữ liệu từ Phú Quý.
- Bảng tỷ giá ngoại tệ lấy dữ liệu từ Vietcombank.
- Bộ chuyển đổi ngoại tệ theo 3 chế độ: mua tiền mặt, mua chuyển khoản, bán.
- Chọn ngày để xem tỷ giá Vietcombank theo từng ngày.
- Xem JSON bảng giá bằng modal dùng chung cho các bảng.
- Biểu đồ lịch sử cập nhật và tooltip chi tiết khi hover điểm dữ liệu.
- UI responsive theo phong cách dashboard, dùng Vite, React, TypeScript và Ant Design.

## Nguồn dữ liệu

- Petrolimex: giá xăng dầu.
- Vang Today: giá vàng.
- Phú Quý: giá bạc.
- Vietcombank: tỷ giá ngoại tệ.

## Ghi chú release

- App thật được build và deploy từ repo `toolhub`.
- Repo này không chứa source app, chỉ là trang ghi chú release.
- Ngày publish: 25/05/2026.
