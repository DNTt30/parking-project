# Parking-Project

## Giới thiệu
Đây là dự án phát hiện chỗ trống bãi đỗ xe sử dụng thị giác máy tính. Hệ thống kết hợp OpenCV để xử lý ảnh và mô hình học sâu (CNN) để phân loại trạng thái ô đỗ (có xe/không có xe).

## Tính năng
- Phát hiện vùng ô đỗ (ROI) bằng phân đoạn ảnh.
- Phân loại trạng thái ô đỗ bằng mô hình CNN.
- Hiển thị kết quả theo thời gian thực.

## Công nghệ sử dụng
- **Ngôn ngữ**: Python
- **Thư viện**: OpenCV, TensorFlow/PyTorch
- **Dữ liệu**: Bộ dữ liệu PKLot, CNRPark

## Cài đặt
```bash
git clone https://github.com/DNTt30/parking-project.git
cd parking-project
pip install -r requirements.txt
