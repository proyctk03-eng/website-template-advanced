# [Thực hành] Tạo Website Template Có Giao Diện Đẹp Mắt

Bài thực hành nâng cao xây dựng template trang web hiện đại kết hợp hình nền, hiệu ứng mờ (blur), menu cố định khi cuộn và bố cục CSS Grid / Flexbox theo chuẩn CodeGym.

## Cấu trúc thư mục dự án
```
website-template-advanced/
├── index.html
├── README.md
├── css/
│   └── style.css
└── images/
    ├── banner.jpg   (Hình nền header)
    ├── service1.jpg (Hình dịch vụ Thiết kế Website)
    ├── service2.jpg (Hình dịch vụ SEO & Marketing)
    └── service3.jpg (Hình dịch vụ Hỗ trợ 24/7)
```

## Các tính năng nổi bật
- **Header**: Nền ảnh phủ gradient và hiệu ứng blur kính mờ hiện đại (`backdrop-filter / filter: blur`).
- **Fixed Navigation**: Menu điều hướng cố định trên cùng (`position: fixed`) với hiệu ứng chuyển màu khi hover.
- **Card Layout (CSS Grid)**: Danh sách dịch vụ được chia thành lưới 3 cột đều nhau (`grid-template-columns: repeat(3, 1fr)`), kèm hiệu ứng phóng to nhẹ khi hover (`transform: scale(1.05)`).
- **Footer**: Bố cục 2 cột chuyên nghiệp (`display: flex; justify-content: space-between`) với các mục phân cấp bằng dấu chấm (`•`).
