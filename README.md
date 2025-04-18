# KMEANS TESTER FOR MACHINE LEARNING
---

[![Install with Docker in VS Code](https://img.shields.io/badge/VS_Code-Install_Server-0098FF?style=flat-square&logo=visualstudiocode&logoColor=white)](https://insiders.vscode.dev/redirect/mcp/install?name=github&inputs=%5B%7B%22id%22%3A%22github_token%22%2C%22type%22%3A%22promptString%22%2C%22description%22%3A%22GitHub%20Personal%20Access%20Token%22%2C%22password%22%3Atrue%7D%5D&config=%7B%22command%22%3A%22docker%22%2C%22args%22%3A%5B%22run%22%2C%22-i%22%2C%22--rm%22%2C%22-e%22%2C%22GITHUB_PERSONAL_ACCESS_TOKEN%22%2C%22ghcr.io%2Fgithub%2Fgithub-mcp-server%22%5D%2C%22env%22%3A%7B%22GITHUB_PERSONAL_ACCESS_TOKEN%22%3A%22%24%7Binput%3Agithub_token%7D%22%7D%7D)

---

- K-means clustering là một kỹ thuật được sử dụng để sắp xếp dữ liệu thành các nhóm dựa trên mức độ tương đồng của chúng.

- Thuật toán hoạt động bằng cách đầu tiên chọn ngẫu nhiên một số điểm trung tâm được gọi là tâm điểm và sau đó mỗi điểm dữ liệu được gán cho tâm điểm gần nhất tạo thành một cụm. Sau khi tất cả các điểm được gán cho một cụm, tâm điểm được cập nhật bằng cách tìm vị trí trung bình của các điểm trong mỗi cụm. Quá trình này lặp lại cho đến khi tâm điểm ngừng thay đổi, tạo thành các cụm. Mục tiêu của phân cụm là chia các điểm dữ liệu thành các cụm sao cho các điểm dữ liệu tương tự thuộc cùng một nhóm.

---

## K-means clustering  hoạt động như thế nào?
- Khi được cung cấp một tập dữ liệu với các đặc điểm và giá trị (vectơ). Nhiệm vụ chính là phân loại dữ liệu thành các nhóm. Chúng ta sẽ sử dụng thuật toán K-means. ‘K’ trong tên của thuật toán biểu thị số nhóm/cụm mà chúng ta muốn phân loại các mục của mình thành.
<p align="left">
  <img src="https://drive.google.com/uc?id=1SLzuB5Jx7gwmlNUTq3TFsEOoaFHbimGd" alt="Example Image" style="width:50%; height:auto;">
</p>
<p>1. Đầu tiên, chúng ta khởi tạo ngẫu nhiên k điểm, được gọi là trung bình hoặc trọng tâm cụm.</p>
<p>2. Chúng ta phân loại từng mục theo giá trị trung bình gần nhất và cập nhật tọa độ của giá trị trung bình (là giá trị trung bình của các mục được phân loại trong cụm đó).</p>
<p>3. Chúng ta lặp lại quy trình này trong một số lần lặp nhất định và cuối cùng, chúng ta có các cụm.</p>

---

## Mô hình sau khi được phân cụm thành công
<p align="left">
  <img src="https://drive.google.com/file/d/18Lb6_cTRinQK8OEj-PD8pmaER7IiSxDf" alt="Example Image" style="width:50%; height:auto;">
</p>

---
### Tóm lại, K-means clustering là một thuật toán học máy không giám sát mạnh mẽ để nhóm các tập dữ liệu không có nhãn. Mục tiêu: chia dữ liệu thành các cụm, biến các điểm dữ liệu tương tự thành một phần của cùng một nhóm. Thuật toán khởi tạo các tâm cụm và gán lặp lại các điểm dữ liệu cho tâm gần nhất, cập nhật các tâm dựa trên giá trị trung bình của các điểm trong mỗi cụm.


