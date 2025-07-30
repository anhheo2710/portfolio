# 😄 Facial Expression Recognition with CNN

## Mô tả

Dự án áp dụng mô hình học sâu (Convolutional Neural Networks - CNN) để nhận diện cảm xúc trên khuôn mặt người từ ảnh tĩnh. Dữ liệu sử dụng là tập FER2013 gồm 48x48 ảnh grayscale.

## Dataset
- **Nguồn**: FER2013 (Facial Expression Recognition)  
- **Số lượng mẫu**: ~35,000 ảnh phân loại theo 7 cảm xúc:
  - Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral

## Mô hình
- CNN gồm nhiều tầng convolution + pooling
- Hàm kích hoạt ReLU
- Batch Normalization
- Dropout để giảm overfitting
- Softmax classifier ở output layer

## Kết quả
- Accuracy ~ 66% trên tập validation
- Confusion matrix thể hiện mô hình phân biệt tốt các cảm xúc như *Happy* và *Neutral*

## Hình ảnh minh họa
- Biểu đồ loss/accuracy qua các epoch
- Confusion matrix
- Ví dụ ảnh nhận diện đúng/sai cảm xúc

## Công cụ sử dụng
- Python (Keras, TensorFlow)
- Google Colab

## Repo liên quan
- [Xem mã nguồn gốc tại đây](https://github.com/anhheo2710/Fundamental-ML)

---

📁 Thư mục:
- `notebooks/`: Notebook huấn luyện và đánh giá mô hình
- `images/`: Hình ảnh minh họa kết quả mô hình

