# Cách dùng bộ README + animated asset này

Repository profile của bạn cần có cấu trúc:

```text
Dle28/
├── README.md
└── assets/
    └── dung-le-animated-banner.svg
```

## Cập nhật bằng terminal

```bash
cd /home/dungle/Downloads

git clone https://github.com/Dle28/Dle28.git Dle28_profile_animated

cp DungLe_GitHub_Profile_Animated/README.md \
   Dle28_profile_animated/README.md

mkdir -p Dle28_profile_animated/assets

cp DungLe_GitHub_Profile_Animated/assets/dung-le-animated-banner.svg \
   Dle28_profile_animated/assets/dung-le-animated-banner.svg

cd Dle28_profile_animated

git add README.md assets/dung-le-animated-banner.svg
git commit -m "Add animated Dũng Lê profile banner"
git push origin main
```

Sau đó mở `https://github.com/Dle28`.

Nếu GitHub còn hiện nút **Share to Profile**, hãy bấm nút đó.

## Hiệu ứng có trong asset SVG

- chữ tên phát sáng nhẹ
- sao nhấp nháy
- khối pixel trôi chậm
- đường dữ liệu chạy động
- cột biểu đồ nhấp nhô
- mạng node ở góc phải phát sáng nhẹ
