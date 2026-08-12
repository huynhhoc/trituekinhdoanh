# Notebook thực hành Trí tuệ kinh doanh

**Huỳnh Thái Học**<br>
Khoa Khoa học dữ liệu trong kinh doanh — Đại học Ngân hàng

- `chuong1/bai_tap_minh_hoa_chuong1.ipynb`: Python nền tảng dùng tiếp cho
  Chương 2 (mô tả), Chương 3 (dự báo) và Chương 4 (đề xuất).
- `chuong2/bai_tap_minh_hoa_chuong2.ipynb`: pipeline phân tích mô tả hoàn chỉnh
  từ grain/chất lượng dữ liệu đến OLAP, dashboard Python, Tableau và insight.
- `chuong3/bai_tap_thuc_hanh_chuong3.ipynb`: thực hành CRISP-DM, pipeline dự
  đoán, baseline, đánh giá, threshold, clustering và luật kết hợp.

Mỗi notebook tự sinh dữ liệu mẫu, không phụ thuộc file ngoài và có thể tải trực
tiếp lên Google Colab rồi chọn **Runtime → Run all**.

Notebook Chương 2 xuất `buh_mart_q2_2026_clean.csv` để dùng cho phần thực
hành Tableau và cung cấp bảng đối soát số liệu Python–Tableau.

Tái tạo notebook sau khi chỉnh nội dung bằng lệnh:

```bash
python3 tools/build_colab_notebooks.py
python3 tools/build_chapter3_notebook.py
```
