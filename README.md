# Trí tuệ kinh doanh — Business Intelligence

Kho học liệu và bài tập thực hành của học phần **Trí tuệ kinh doanh**
(*Business Intelligence*), mã học phần **BIN701**.

**Giảng viên:** Huỳnh Thái Học<br>
**Đơn vị:** Khoa Khoa học dữ liệu trong kinh doanh — Đại học Ngân hàng

> Học phần hướng đến việc sử dụng dữ liệu, công cụ phân tích và mô hình hỗ trợ
> quyết định để hiểu hiện trạng, dự đoán kết quả và lựa chọn hành động phù hợp
> trong kinh doanh.

## Thông tin học phần

| Nội dung | Thông tin |
|---|---|
| Tên học phần | Trí tuệ kinh doanh (*Business Intelligence*) |
| Mã học phần | BIN701 |
| Số tín chỉ | 03 |
| Thời lượng | 150 giờ: 45 giờ trên lớp và 105 giờ tự học, tự nghiên cứu |
| Hình thức | Trực tiếp kết hợp trực tuyến; trực tuyến không quá 30% thời gian giảng dạy |
| Giảng viên | Huỳnh Thái Học |
| Đơn vị quản lý | Khoa Khoa học dữ liệu trong kinh doanh — Đại học Ngân hàng |
| Học phần trước | Khoa học dữ liệu cho kinh doanh |

## Chuẩn đầu ra học phần

| CLO | Mức độ | Chuẩn đầu ra |
|---|---:|---|
| CLO1 | 3 | Diễn giải các thuật ngữ hệ hỗ trợ quyết định (DSS), trí tuệ kinh doanh (BI) và phân tích kinh doanh (BA). |
| CLO2 | 4 | Áp dụng phân tích mô tả để tạo thông tin và sản phẩm BI phục vụ bài toán quản trị. |
| CLO3 | 3 | Áp dụng phân tích dự đoán và hệ hỗ trợ quyết định dựa trên dữ liệu. |
| CLO4 | 3 | Áp dụng phân tích đề xuất và hệ hỗ trợ quyết định dựa trên mô hình. |

Năng lực tích hợp của học phần là chuyển vấn đề quản trị thành câu hỏi dữ liệu,
xây dựng sản phẩm phân tích, giải thích kết quả và đề xuất hành động phù hợp với
mục tiêu, ràng buộc và bối cảnh kinh doanh.

## Lộ trình nội dung

| Chương | Thời lượng | CLO | Nội dung chính |
|---|---:|---|---|
| Chương 1 — Nền tảng DSS, BI và BA | 10 giờ | CLO1 | Quá trình ra quyết định quản lý; phân biệt DSS, BI, BA; cộng tác, trách nhiệm và đạo đức. |
| Chương 2 — Phân tích mô tả và BI | 15 giờ | CLO2 | Chất lượng dữ liệu, KPI, thống kê tóm tắt, OLAP, trực quan hóa và dashboard. |
| Chương 3 — Phân tích dự đoán | 10 giờ | CLO3 | Quy trình khai phá dữ liệu, hồi quy, phân lớp, phân cụm và đánh giá mô hình. |
| Chương 4 — Phân tích đề xuất | 10 giờ | CLO4 | Phân tích quyết định, tối ưu hóa, ràng buộc, độ nhạy và mô phỏng. |

### Chương 1 — Hiểu quyết định cần hỗ trợ

Sinh viên phân tích một tình huống quản trị để xác định:

- vấn đề và quyết định cần hỗ trợ;
- dữ liệu cần thu thập;
- loại phân tích phù hợp;
- các phương án và tiêu chí lựa chọn;
- rủi ro, trách nhiệm và điểm cần con người phê duyệt.

Notebook Chương 1 cung cấp thêm các bài Python nhập môn làm nền tảng cho phần
thực hành ở Chương 2–4.

### Chương 2 — Mô tả đúng hiện trạng

Quy trình thực hành đi từ dữ liệu thô đến sản phẩm BI:

```text
Dữ liệu thô → Làm sạch → Chỉ số/KPI → OLAP → Biểu đồ → Dashboard → Insight
```

Sinh viên thực hành xác định grain, xử lý chất lượng dữ liệu, tính KPI, phân
tích đa chiều bằng slice/dice và pivot, xây dựng dashboard, đối soát số liệu và
diễn giải kết quả cho nhà quản lý.

### Chương 3 — Dự đoán kết quả chưa biết

Sinh viên chuyển câu hỏi kinh doanh thành bài toán học máy, chuẩn bị dữ liệu,
xây dựng và đánh giá mô hình trên dữ liệu chưa thấy. Nội dung nhấn mạnh kiểm
soát overfitting, rò rỉ dữ liệu và diễn giải đầu ra dự báo trong bối cảnh quyết
định.

### Chương 4 — Lựa chọn hành động dưới ràng buộc

Sinh viên kết hợp dự báo và giả định kinh doanh để xây dựng phương án, biến
quyết định, hàm mục tiêu và ràng buộc; sau đó sử dụng Excel Solver hoặc Python
để tối ưu và kiểm tra độ bền bằng phân tích độ nhạy, tình huống hoặc mô phỏng
Monte Carlo.

## Phương pháp dạy và học

Học phần kết hợp:

- thuyết giảng để hệ thống hóa kiến thức nền tảng;
- bài giảng tương tác và bài tập ngắn;
- thảo luận tình huống dựa trên bằng chứng;
- thực hành cá nhân trên máy tính;
- học theo nhóm để xây dựng sản phẩm và báo cáo.

Người học cần chuẩn bị học liệu và máy tính khi được yêu cầu, tham gia đầy đủ,
hoàn thành phần tự học và ghi rõ nguồn trích dẫn trong mọi sản phẩm.

## Công cụ

| Công cụ | Vai trò trong học phần |
|---|---|
| Python / Google Colab | Xử lý dữ liệu, phân tích mô tả, mô hình dự đoán và tối ưu hóa |
| Pandas, Matplotlib, Seaborn | Làm sạch, tổng hợp và trực quan hóa dữ liệu |
| Tableau | Phân tích đa chiều, trực quan hóa và dashboard tương tác |
| RapidMiner | Xây dựng quy trình và mô hình dự đoán |
| Excel / Solver | Mô hình quyết định và tối ưu hóa dưới ràng buộc |

## Cơ cấu đánh giá

| Thành phần | Tỷ trọng | Hình thức |
|---|---:|---|
| Chuyên cần | 10% | Đánh giá trong suốt học phần: hiện diện 40%, tham gia 60% |
| Kiểm tra trên máy | 20% | 02 bài cá nhân; đánh giá CLO1, CLO2 và CLO3 |
| Bài tập lớn và bài tập về nhà | 20% | 02 đợt; cá nhân hoặc nhóm tối đa 5; nộp báo cáo và chương trình; đánh giá CLO1–CLO4 |
| Cuối kỳ | 50% | 01 dự án nhóm, nộp không thuyết trình; thực hiện trong 1–7 ngày làm việc; đánh giá CLO1–CLO4 |

Rubric kiểm tra trên máy gồm: lý luận 40%, lập luận 40% và văn phong 20%.
Rubric dự án/cuối kỳ gồm: lập trình 25%, cơ sở lý luận 25%, văn phong khoa học
25% và hình thức báo cáo 25%.

> Mọi sản phẩm phải ghi nguồn. Liêm chính học thuật được thực hiện theo quy chế
> đào tạo.

## Cấu trúc kho học liệu

```text
.
├── tai-lieu/
│   ├── chuong1/       # Slide lý thuyết Chương 1
│   └── chuong2/       # Slide lý thuyết Chương 2
│   └── chuong3/       # Slide lý thuyết Chương 3
│   └── chuong4/       # Slide lý thuyết Chương 4
└── src/
    ├── chuong1/       # Notebook Python nền tảng
    ├── chuong2/       # Notebook phân tích mô tả
    └── chuong3/       # Notebook phân tích dự đoán
    └── chuong4/       # Notebook phân tích đề xuất
```

Các notebook tự sinh dữ liệu mô phỏng, không phụ thuộc file dữ liệu bên ngoài.
Để sử dụng, tải file `.ipynb` lên [Google Colab](https://colab.research.google.com/)
và chọn **Runtime → Run all**.

## Lộ trình học hiệu quả

1. **Trước lớp:** đọc slide và tài liệu, ghi lại thuật ngữ hoặc câu hỏi chưa rõ.
2. **Tại lớp:** tham gia thảo luận, chạy ví dụ và giải thích kết quả thay vì chỉ sao chép mã.
3. **Sau lớp:** hoàn thành bài tập, đối soát kết quả và viết insight gắn với quyết định.
4. **Trước chương tiếp theo:** ôn lại dữ liệu và sản phẩm của chương trước vì các chương được thiết kế liên thông.

## Học liệu chính

1. Sharda, R., Delen, D., & Turban, E. (2020). *Analytics, Data Science, & Artificial Intelligence: Systems for Decision Support*. Pearson.
2. Page, S. E. (2021). *The Model Thinker*. Basic Books.
3. Davenport, T. H. (2017). *Competing on Analytics*. Harvard Business Review Press.

Học liệu bổ trợ:

- Provost, F., & Fawcett, T. (2013). *Data Science for Business*. O'Reilly Media.
- Power, D. J. (2002). *Decision Support Systems: Concepts and Resources for Managers*. Quorum Books.
- Simon, H. A. (1977). *The New Science of Management Decision*. Prentice-Hall.

---

Nội dung học phần và chuẩn đầu ra được biên soạn theo đề cương **BIN701 — 2026**.
Dữ liệu trong các notebook là **dữ liệu mô phỏng phục vụ học tập**.
