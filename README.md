# SQL Analysis Project: Ecommerce Exploration

---

### **I. Project Assumption**
Our company runs business in E-Commerce field. Stakeholders have 8 questions about collected data. As a data analst, I need to explore, analyze the data and give answers by using:
- Data source: bigquery-public-data.google_analytics_sample
- Data set: bigquery-public-data.google_analytics_sample.ga_sessions_20170801 
- Tool: Google Bigquery

### **II. Data Exploration**
  1. What is total visits, pageviews, transactions for Jan, Feb and March 2017?
  2. What is bounce rate per traffic source in July 2017?
  3. What is revenue by traffic source by week, by month in June 2017?
  4. What is average number of pageviews by purchaser type (purchasers vs non-purchasers) in June, July 2017?
  5. What is average number of transactions per user that made a purchase in July 2017?
  6. What is average amount of money spent per session. Only include purchaser data in July 2017?
  7. What are other products purchased by customers who purchased product "YouTube Men's Vintage Henley" in July 2017?
  8. What is cohort map from product view to addtocart to purchase in Jan, Feb and March 2017?

#### **3. Kỹ thuật sử dụng**
- **Truy vấn SQL chính:** [GROUP BY, JOIN, WINDOW FUNCTION, CTEs]
- **Tối ưu hóa:** Indexing, Partitioning, Subqueries (nếu có)

---

### **Cách chạy dự án**
1. **Cài đặt môi trường:**
   - Yêu cầu: [PostgreSQL/MySQL/SQLite, Python (nếu dùng thêm phân tích)]
   - Cài đặt: `pip install psycopg2` (nếu liên kết với Python)
2. **Chạy các script SQL:**
   - Import dữ liệu: `01_import_data.sql`
   - Phân tích dữ liệu: `02_analysis_queries.sql`
3. **Xem kết quả:**
   - Truy cập file kết quả: `results/summary.csv`

---

### **Kết quả**
- Bảng dashboard hoặc hình ảnh kết quả phân tích.
- Liệt kê những insight chính:
  - Ví dụ: "Doanh thu tăng 20% vào tháng 12 so với tháng 11."
  - "Khách hàng từ khu vực miền Bắc đóng góp 50% doanh thu."

---

### **Thư mục Dự án**
```plaintext
├── data/
│   ├── customers.csv
│   ├── transactions.csv
├── queries/
│   ├── 01_import_data.sql
│   ├── 02_analysis_queries.sql
├── results/
│   ├── summary.csv
├── README.md
