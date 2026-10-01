# BÀI TẬP THỰC HÀNH BUỔI 01: XÂY DỰNG TRANG GIỚI THIỆU SẢN PHẨM / CÔNG NGHỆ BẰNG HTML

> **Học viện Công nghệ Bưu chính Viễn thông (PTIT)**  
> **Khoa Công nghệ Thông tin** - Môn học: Lập trình Web  
> **Giảng viên hướng dẫn:** Thầy Trần Tiến Anh ([anhtt2@ptit.edu.vn](mailto:anhtt2@ptit.edu.vn))  
> **Sinh viên thực hiện:** Phạm Xuân Kỳ  
> **Mã sinh viên:** B23DCCC092  
> **Lớp:** D23CNTT  
> **Repository GitHub:** [https://github.com/kydeptrai1209/B23DCCC092-PhamXuanKy-Web](https://github.com/kydeptrai1209/B23DCCC092-PhamXuanKy-Web)  
> **Chủ đề lựa chọn:** **Visual Studio Code (VS Code)** - Trình soạn thảo mã nguồn phổ biến hàng đầu thế giới.

---

## 📌 1. Giới Thiệu Đồ Án

Trang web được xây dựng hoàn toàn bằng **HTML thuần (Pure Semantic HTML)** theo đúng yêu cầu của buổi thực hành đầu tiên:
- Không sử dụng CSS và JavaScript.
- Không sử dụng template dựng sẵn từ bên ngoài.
- Tuân thủ tiêu chuẩn ngữ nghĩa của HTML5 (`<header>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<footer>`).
- Trình bày thông tin rõ ràng, khoa học, dễ đọc, dễ giải thích.

---

## 📋 2. Báo Cáo Chi Tiết Yêu Cầu & Tính Năng Đã Hoàn Thành

| Mục Yêu Cầu | Tiêu Chí Chi Tiết | Trạng Thái | Mô Tả Thực Hiện Trong Bài |
|---|---|:---:|---|
| **A. Tiêu đề & Giới thiệu** | • Tên sản phẩm dùng thẻ heading (`<h1>`).<br>• Đoạn văn giới thiệu ngắn (`<p>`).<br>• Trình bày sản phẩm dùng để làm gì (`<p>`, `<ul>`). | **ĐẠT (100%)** | Tiêu đề lớn về Visual Studio Code, đoạn văn giới thiệu lịch sử Microsoft phát triển từ 2015, danh sách 5 mục đích sử dụng cốt lõi của công cụ. |
| **B. Hình ảnh minh họa** | • Có ít nhất 02 hình ảnh liên quan.<br>• Thẻ `<img>` đầy đủ thuộc tính `src`, `alt`, `width`, `height`.<br>• Ảnh lưu trong thư mục `images/`. | **ĐẠT (100%)** | 02 hình ảnh vector SVG sắc nét:<br>1. `images/vscode-logo.svg`: Logo biểu trưng Microsoft VS Code.<br>2. `images/vscode-interface.svg`: Ảnh mô phỏng giao diện Explorer, Editor, Terminal của VS Code. |
| **C. Đặc điểm nổi bật** | • Sử dụng danh sách `<ul>` hoặc `<ol>`.<br>• Liệt kê ít nhất 05 đặc điểm/tính năng nổi bật. | **ĐẠT (100%)** | Sử dụng thẻ `<ol>` đánh số thứ tự liệt kê **07 đặc điểm nổi bật**: Đa ngôn ngữ, IntelliSense, Git tích hợp, Debugger chuyên nghiệp, Extensions Marketplace, Terminal tích hợp, Live Share. |
| **D. Bảng thông tin** | • Sử dụng `<table>`, `<tr>`, `<th>`, `<td>`.<br>• Ít nhất 03 cột và ít nhất 04 dòng dữ liệu. | **ĐẠT (100%)** | Bảng thông số cấu hình và tương thích hệ điều hành gồm **04 cột** (*Tiêu chí, Windows, macOS, Linux*) và **06 dòng dữ liệu** (*HĐH hỗ trợ, CPU, RAM tối thiểu/khuyến nghị, Ổ cứng, Kiến trúc, Bản quyền*). |
| **E. Ưu điểm & Hạn chế** | • Khu vực Ưu điểm: Ít nhất 03 ưu điểm.<br>• Khu vực Hạn chế: Ít nhất 02 hạn chế.<br>• Dùng danh sách HTML `<ul>`/`<ol>`. | **ĐẠT (100%)** | Hai phân mục rõ ràng:<br>• **05 Ưu điểm:** Miễn phí, khởi động nhanh, nhiều extension, tùy biến cao, cộng đồng lớn.<br>• **03 Hạn chế:** Cần cài thêm compiler, tốn RAM do Electron khi mở dự án lớn, nhiều setting cho người mới. |
| **F. Liên kết tham khảo** | • Ít nhất 02 liên kết đến nguồn liên quan.<br>• Thẻ `<a>` và thuộc tính `href`. | **ĐẠT (100%)** | **04 liên kết chính thức** có thẻ `<a>` kèm thuộc tính `href`, `target="_blank"`, `rel="noopener noreferrer"`: Trang chủ VS Code, Trang tài liệu docs, Trang Marketplace, Kho GitHub microsoft/vscode. |
| **Cấu trúc trang** | • Sử dụng các thẻ cấu trúc ngữ nghĩa có ý nghĩa. | **ĐẠT (100%)** | Áp dụng chuẩn semantic: `<header>`, `<main>`, `<section>`, `<footer>`, `<figure>`, `<figcaption>`. |
| **Cấu trúc thư mục** | • Định dạng thư mục: `MaSinhVien_HoTen_Buoi1`. | **ĐẠT (100%)** | Thư mục `B23DCCC092_PhamXuanKy_Buoi1` chứa đầy đủ `index.html` và thư mục `images/`. |
| **Tên Repository** | • Định dạng: `MaSinhVien-HoTen-Web`. | **ĐẠT (100%)** | Repository: `B23DCCC092-PhamXuanKy-Web`. |

---

## 📁 3. Cấu Trúc Thư Mục Trong Repository

```
B23DCCC092-PhamXuanKy-Web/
│
├── README.md                                  # Báo cáo chi tiết đồ án
├── index.html                                 # Trang HTML gốc của repository
│
├── images/                                    # Thư mục hình ảnh minh họa
│   ├── vscode-logo.svg                        # Biểu trưng Visual Studio Code
│   └── vscode-interface.svg                   # Giao diện làm việc Visual Studio Code
│
└── B23DCCC092_PhamXuanKy_Buoi1/               # Thư mục đúng chuẩn quy định của giảng viên
    ├── index.html                             # File HTML bài nộp buổi 1
    └── images/                                # Thư mục ảnh phục vụ buổi 1
        ├── vscode-logo.svg
        └── vscode-interface.svg
```

---

## 🚀 4. Hướng Dẫn Xem Bài Nộp

1. **Xem trực tiếp trên máy tính:**
   - Clone repository về máy:
     ```bash
     git clone https://github.com/kydeptrai1209/B23DCCC092-PhamXuanKy-Web.git
     ```
   - Nhấp đúp chuột vào file `index.html` hoặc file `B23DCCC092_PhamXuanKy_Buoi1/index.html` để mở bằng bất kỳ trình duyệt web nào (Chrome, Edge, Firefox, Cốc Cốc,...).

2. **Xem trực tuyến trên GitHub:**
   - Truy cập: [https://github.com/kydeptrai1209/B23DCCC092-PhamXuanKy-Web](https://github.com/kydeptrai1209/B23DCCC092-PhamXuanKy-Web)

---

## 👤 5. Thông Tin Tác Giả

- **Sinh viên:** Phạm Xuân Kỳ
- **Mã sinh viên:** B23DCCC092
- **Lớp:** D23CNTT
- **Email cá nhân:** [phamky136@gmail.com](mailto:phamky136@gmail.com)
- **Học viện Công nghệ Bưu chính Viễn thông (PTIT)**
