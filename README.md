
# StudyMate Light – Smart Study Dashboard

**StudyMate Light** là dashboard web hỗ trợ quản lý thời gian học tập, theo dõi ánh sáng, và tích hợp thiết bị (Serial / BLE).  
Dự án này dùng **React 18 + Tailwind + Recharts + Lucide Icons** qua CDN, chạy độc lập mà không cần backend.

## 🚀 Demo
Khi deploy lên GitHub Pages:  
`https://<tên-github>.github.io/studymate-light/`

## ⚡ Tính năng
- Pomodoro Timer + thống kê.
- Lịch sử học tập (localStorage).
- Tích hợp Serial/BLE (stub sẵn sàng nối firmware).
- Biểu đồ trực quan (Recharts).
- UI hiện đại (Tailwind + Lucide).

## 🛠 Cài đặt & Chạy thử
```bash
git clone https://github.com/<tên-github>/studymate-light.git
cd studymate-light
# Chạy offline
open index.html   # (hoặc double-click)
```

## 🌐 Deploy miễn phí
### GitHub Pages
1. Push repo này lên GitHub.
2. Vào **Settings → Pages**.
3. Chọn **Deploy from a branch** → Branch: `main` → Save.
4. Link sẽ có dạng: `https://<tên-github>.github.io/studymate-light/`

### Netlify
- Vào https://app.netlify.com/drop → kéo-thả toàn bộ thư mục repo.

### Vercel
- Import repo này vào https://vercel.com → Deploy.

## 📜 License
MIT License (xem [LICENSE](./LICENSE)).
