# 🚀 Edtronaut B2B Enterprise Suite — IT BA / PO Case Study

Tài liệu này tổng hợp toàn bộ giải pháp nghiệp vụ, tài liệu đặc tả hệ thống (PRD/SRS), sơ đồ quy trình chuẩn (BPMN 2.0 / Swimlane) và thiết kế UI/UX Mockup cho dự án **Chuyển đổi Nền tảng Edtronaut B2C sang B2B Enterprise Suite**. 

Dự án này được thiết kế và thực hiện như một bài kiểm tra năng lực (Take-home Assignment v2.0) cho vị trí **IT Business Analyst / Product Owner Intern**.

---

## 🌟 Demo & Tài Liệu Trực Quan

- **Interactive Slide Deck (Web Demo):** [Mở file index.html](index.html) *(Xem trực tiếp slide báo cáo 15 trang tương tác mượt mà bằng HTML/CSS).*
- **Bản slide PDF gốc:** [Edtronaut_B2B_Case_Study_Deck.pdf](Edtronaut_B2B_Case_Study_Deck.pdf)
- **Tài liệu Đặc tả Chi tiết (Markdown):** [EDTRONAUT_BA_INTERN_ASSIGNMENT.md](EDTRONAUT_BA_INTERN_ASSIGNMENT.md)
- **File Word Báo cáo nộp bài:** [Edtronaut_BA_PO_Assignment_Submission.docx](Edtronaut_BA_PO_Assignment_Submission.docx)

---

## 🛠️ Nội Dung Case Study

Case study giải quyết bài toán cốt lõi: **Làm sao dịch chuyển mô hình B2C mô phỏng (S.O.R.A Simulation Engine) của Edtronaut sang giải pháp B2B SaaS phục vụ doanh nghiệp** trong 3 phân hệ:
1. **Hiring Automation (Tuyển dụng tự động):** Sàng lọc hồ sơ bằng dữ liệu kỹ năng thực chiến (Simulation Score) thay vì CV truyền thống.
2. **Guided Onboarding (Hội nhập nhân sự mới):** Chuẩn hóa lộ trình thử việc, tạo vòng lặp phản hồi đóng giữa nhân viên mới và quản lý trực tiếp.
3. **Continuous Upskilling (Đào tạo liên tục):** Bản đồ kỹ năng (Skill Matrix) tự động và kích hoạt tín hiệu đề xuất thăng chức (Promotion Signal) dựa trên năng lực đo lường được.

### Các tài liệu kỹ thuật & nghiệp vụ bàn giao trong repo:
- **6 Persona chi tiết** bao quát toàn bộ Stakeholders (TA Recruiter, Candidate, New Hire, HR Ops, Employee, L&D Manager).
- **3 Sơ đồ quy trình chuẩn:**
  - *Hiring Automation Process:* Vẽ theo chuẩn **BPMN 2.0 Swimlane** với tính năng **Flow Manager** (tráo đổi bước Sim và Phỏng vấn linh hoạt).
  - *Onboarding Process:* Sơ đồ **Cross-Functional Swimlane Flowchart** với vòng lặp sửa đổi (Closed-loop feedback).
  - *Upskilling Loop:* Sơ đồ **Continuous Closed-Loop** thể hiện vòng lặp phát triển kỹ năng và thăng tiến liên tục.
- **Tài liệu đặc tả (PRD/SRS) cho Recruitment Dashboard:**
  - Phân tích luồng (User Flow) & Mô hình thực thể liên kết (Relational Data Model).
  - Cấu trúc API Payload kết nối với SORA Engine.
  - Phân quyền RBAC Matrix.
  - 5 yêu cầu phi chức năng (NFR) khắt khe (Performance, Security PII AES-256, Audit Log, PDPA/GDPR compliance).
- **UI/UX Mockup độ nét cao:** Mô phỏng giao diện Trang quản lý danh sách ứng viên (Pipeline Dashboard) và Trang chi tiết ứng viên (Candidate Profile View) được vẽ tinh tế bằng mã HTML trực tiếp.
- **Kịch bản kiểm thử (Acceptance Criteria):** Soạn thảo chuẩn **Gherkin format** (Given-When-Then) sẵn sàng cho đội ngũ QA Automation.
- **Lộ trình phát triển 6 tuần (Roadmap):** Phân chia Sprint Agile/Scrum kèm bảng quản trị rủi ro (Risk Register Matrix) & KPI đo lường sau 30 ngày launch.

---

## 📂 Cấu Trúc Thư Mục Repo

```text
├── assets/                          # Chứa toàn bộ hình ảnh và sơ đồ BPMN
│   ├── edtronaut_logo.jpg
│   ├── duy_thien_do.jpg             # Ảnh chân dung ứng viên
│   ├── Hiring.png                   # Sơ đồ BPMN 2.0 Hiring
│   ├── New BPMN diagram.png         # Sơ đồ Sub-process Assessment Loop
│   ├── Sub process 2.png            # Sơ đồ Sub-process Interview & Offer
│   ├── Figure B.2 New Hire...png    # Sơ đồ Onboarding Swimlane
│   └── Figure B.3 Upskilling...png  # Sơ đồ Upskilling Continuous Loop
├── index.html                       # Slide tương tác web (Web Demo)
├── EDTRONAUT_BA_INTERN_ASSIGNMENT.md# Đặc tả chi tiết (BA Deliverables)
├── Edtronaut_B2B_Case_Study_Deck.pdf# Bản PDF slide thuyết trình
└── Edtronaut_BA_PO_Assignment_Submission.docx # Tài liệu Word nộp bài
```

---

## 🚀 Hướng Dẫn Đưa Lên GitHub & Bật Web Demo (GitHub Pages)

Để biến thư mục này thành một portfolio cá nhân trực tuyến, bạn có thể thực hiện theo các bước sau:

### Bước 1: Tạo Git Repository cục bộ
Mở Terminal tại thư mục `edtronaut-portfolio` này và chạy các lệnh:
```bash
git init
git add .
git commit -m "feat: init portfolio for Edtronaut B2B Case Study"
```

### Bước 2: Tạo Repo mới trên GitHub
1. Truy cập [github.com/new](https://github.com/new) và đăng nhập tài liệu cá nhân của bạn.
2. Đặt tên Repo (ví dụ: `edtronaut-b2b-case-study-portfolio`).
3. Chọn chế độ **Public**. Không chọn thêm README hay .gitignore (vì ta đã có sẵn).
4. Nhấn **Create repository**.

### Bước 3: Đẩy code lên GitHub
Sao chép 3 dòng lệnh GitHub hiển thị ở trang mới và chạy trong terminal cục bộ của bạn (thay URL bằng URL repo của bạn):
```bash
git branch -M main
git remote add origin https://github.com/<your-username>/edtronaut-b2b-case-study-portfolio.git
git push -u origin main
```

### Bước 4: Bật GitHub Pages để chạy Slide Web Demo trực tuyến
1. Trên giao diện Repository của bạn trên GitHub, chọn tab **Settings** (Cài đặt).
2. Tìm đến mục **Pages** ở thanh menu bên trái.
3. Tại phần **Build and deployment** -> **Branch**, chọn nhánh **main** và thư mục là `/ (root)`.
4. Nhấn **Save**.
5. Đợi khoảng 1-2 phút, GitHub sẽ cấp cho bạn một đường link trực tuyến công khai (ví dụ: `https://<your-username>.github.io/edtronaut-b2b-case-study-portfolio/`). 

*Giờ đây bạn có thể đính kèm link này trực tiếp vào CV hoặc Portfolio trực tuyến của mình để nhà tuyển dụng có thể click xem ngay slide tương tác tuyệt đẹp cùng toàn bộ tài liệu BA chi tiết của bạn!*
