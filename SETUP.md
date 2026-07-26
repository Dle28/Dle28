# Cách dùng bộ README không có banner

Repository profile của bạn cần có cấu trúc:

```text
Dle28/
├── README.md
└── assets/
    ├── neon-divider.svg
    └── ai-data-orbit.svg
```

## Cập nhật bằng terminal

```bash
cd /home/dungle/Downloads

git clone https://github.com/Dle28/Dle28.git Dle28_profile_ai_ds

cp DungLe_GitHub_Profile_AI_DS/README.md \
   Dle28_profile_ai_ds/README.md

mkdir -p Dle28_profile_ai_ds/assets

cp DungLe_GitHub_Profile_AI_DS/assets/neon-divider.svg \
   Dle28_profile_ai_ds/assets/neon-divider.svg

cp DungLe_GitHub_Profile_AI_DS/assets/ai-data-orbit.svg \
   Dle28_profile_ai_ds/assets/ai-data-orbit.svg

cd Dle28_profile_ai_ds

git add README.md assets/neon-divider.svg assets/ai-data-orbit.svg
git commit -m "Redesign profile README for AI and Data Science"
git push origin main
```

Sau đó mở:
`https://github.com/Dle28`

Nếu GitHub còn hiện nút **Share to Profile**, hãy bấm nút đó.

## Điểm của bản này

- không dùng banner lớn
- có avatar + card layout
- phong cách riêng, sáng tạo nhưng gọn
- tập trung vào AI + Data Science
- có thêm biểu đồ và thống kê GitHub
