# 🍏 iPhone Customer Support System

Hệ thống **tư vấn & chăm sóc khách hàng** mua iPhone.  
Kết hợp **chatbot AI (RAG)** + **frontend React/Tailwind** + **backend Node.js/REST API**.

---

## 🚀 Tech Stack
- **Frontend**: React + TailwindCSS  
- **Backend**: Node.js (Express) + REST API  
- **Database**: MongoDB  
- **Chatbot**: Retrieval-Augmented Generation (RAG)  
- **DevOps**: GitHub Actions + CI/CD  

---

## 📂 Project Structure (Frontend)

frontend/
│── public/ # Static files
│── src/
│ ├── assets/ # Ảnh, icon, font
│ ├── components/ # UI components (Button, ChatBubble, Navbar…)
│ ├── layouts/ # Layout (MainLayout, AdminLayout…)
│ ├── pages/ # Các trang (Home, Chat, FAQ…)
│ ├── services/ # API call (axios instance)
│ ├── hooks/ # Custom hooks (useChat, useAuth…)
│ ├── context/ # React Context (AuthProvider, ChatProvider)
│ ├── utils/ # Helper function
│ ├── App.jsx # Root component
│ └── main.jsx # Entry point
│── tailwind.config.js
│── package.json


---

## 💡 Key Features
✅ Chatbot trả lời FAQ từ RAG  
✅ Ticket classification theo **region + priority + intent**  
✅ Giao diện quản trị huấn luyện chatbot (upload FAQ, test bot)  
✅ Live chat agent fallback  
✅ Leaderboard đóng góp của team (git-contributor)  

---

## 🏆 Leaderboard Đóng Góp

🔥 Cùng nhau đua TOP để hệ thống ngày càng xịn hơn!  
*(Dữ liệu sẽ tự động cập nhật sau khi nhiều contributors tham gia)*  

<!-- GITCONTRIBUTOR_START -->
| Rank | Contributor | Commits | PRs | Issues |
|------|-------------|---------|-----|--------|
| 🥇   | [@ThienNguyen666](https://github.com/ThienNguyen666) | 12 | 3 | 1 |
| 🥈   | [@user2](https://github.com/user2) | 8 | 2  | 1 |
| 🥉   | [@user3](https://github.com/user3) | 5 | 1  | 0 |
| 🎯   | [@user4](https://github.com/user4) | 3 | 0  | 0 |
<!-- GITCONTRIBUTOR_END -->

---

## 👨‍💻 Contributors

Cảm ơn những người đã đóng góp! 💚  
*(Quản lý bằng [all-contributors](https://allcontributors.org))*  

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/ThienNguyen666"><img src="https://avatars.githubusercontent.com/u/12345678?v=4" width="100px;" alt=""/><br /><sub><b>ThienNguyen666</b></sub></a><br />💻 📖 🚀</td>
  </tr>
</table>
<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

---

## ⚡️ Quick Start

```bash
# clone repo
git clone https://github.com/your-org/iphone-support-system.git

# install frontend
cd frontend
npm install
npm run dev

# install backend
cd ../backend
npm install
npm run dev
```
🔑 Scripts hữu ích

npm run dev → chạy dev mode

npm run build → build production

npm run lint → check code style

npm run format → format code

🌟 Vision

Mục tiêu là xây dựng hệ thống chăm sóc khách hàng thông minh:

Tự động hóa tư vấn qua chatbot

Theo dõi hành vi khách hàng để cải thiện trải nghiệm

Dễ dàng mở rộng thành hệ thống CRM mini cho shop iPhone


---
