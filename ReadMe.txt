Các phần đã thực hiện trong đề tài:
1. Tìm hiểu công nghệ dữ liệu lớn Google Cloud 
   - Tổng quan Google Cloud 
   - Đánh giá ưu nhược điểm 
   - Cách thức triển khai các thành phần theo kiến trúc dữ liệu lớn 
   - Cách sử dụng các công cụ để phân tích dữ liệu mạng xã hội bằng Google Cloud

2. Xây dựng kiến trúc lưu trữ dữ liệu trên Google Cloud 
   - Xây dựng và lập lịch cho data pinelines
   - Lưu trữ dữ liệu trên data lake: Google Storage
   - Lưu trữ dữ liệu trên data warehouse: BigQuery, Neo4J, MongoDB

3. Phân tích và xây dựng mô hình gợi ý kết bạn trên mạng xã hội Meetup 
   - Trích xuất và tiền xử lý dữ liệu từ data warehouse
   - Khảo sát và phân tích dữ liệu (EDA) 
   - Chạy các thuật toán phân tích mạng xã hội
      + Độ đo trung tâm: Degree centrality, Closeness centrality, Betweenness centrality, Eigenvector centrality, Page rank
      + Phát hiện cộng đồng: Louvain
   - Mô hình dự đoán liên kết gợi ý kết bạn
      + Dự đoán dựa trên độ tương đồng cục bộ: Jaccard, Adamic-Adar, Preferential Attachment
      + Dự đoán dựa trên độ tương đồng toàn cục: Hitting time, Katz Global
      + Dự đoán dựa trên máy học: Auto-encoder (GCNConv, GraphSAGEConv)