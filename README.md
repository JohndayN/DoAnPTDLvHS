# DoAnPTDLvHS
Đồ án dựa trên dataset House Price Prediction Dataset Vietnam - 2024
Link Dataset: https://www.kaggle.com/datasets/nguyentiennhan/vietnam-housing-dataset-2024
Sử dụng scikit-learn để chạy MLP

Mục 2: Mục tiêu rõ ràng, và nội dung đề ra phù hợp với mục tiêu 

Mục 3: Nhận xét về chuyên môn 

    3.1. Hiểu được việc mình làm, có sử dụng kiến thức đã được trình bày. 

    3.2. Đối với bài toán phân tích: 

        - Có phân tích diểm bất thường sử dụng z-score, outlier, vẽ boxplot/violin và giải thích hợp lý.
        - Có phân tích tương quan dựa vào hệ số tương quan và hiểu về hệ số tương quan 

        - Có phân tích tương quan dựa vào các phương pháp Machine Learning. 

        - Có phân tích các cycles/frequencies sử dụng thư viện STUMPY hoặc kỹ thuật clustering.
    3.3. Đối với machine learning: 

        - Có loại bỏ dữ liệu bất thường trước khi đưa vào tập huấn luyện và tập kiểm tra.
        - Hiểu được các giá trị tham số hyperparameter: learning rate, epoch, batch-size, ... 

Phân tích dữ liệu 
Hiểu về dữ liệu: Nếu bạn phải giải thích dữ liệu trong đồ án cho một người không 
có chuyên môn về phân tích dữ liệu, bạn sẽ mô tả nó như thế nào? Những thông 
tin quan trọng nhất mà người đó cần biết là gì? 
Câu trả lời: Dữ liệu giá nhà ở Việt Nam có 12 cột và 30229 dòng dữ liệu khác nhau, 12 cột đó là [Address, Area, Fontage, Access Road, House direction, Balcony direction, Floors, Bedrooms, Bathrooms, Legal status, Furniture state, Price] và cột thông tin quan trọng nhất là cột Price
Phát hiện bất thường: Bạn có phát hiện được điểm bất thường (outliers) trong dữ 
liệu không? Nếu có, bạn đã xử lý chúng như thế nào và tại sao?
Câu trả lời: Dữ liệu có các dòng trống trong cột Price, chúng em xử lý bằng cách đưa giá trị trung bình của tất cả cột price vào đó 
Định hướng cải tiến phân tích dữ liệu: Nếu có thêm thời gian, bạn nghĩ mình có 
thể cải thiện phần phân tích dữ liệu của đồ án như thế nào? Hãy đề xuất ít nhất một 
cách tiếp cận khác mà bạn chưa thử. 
Câu trả lời: Nếu dư thời gian, chúng em sẽ tập trung phân tích thêm vào chu kỳ của dữ liệu do bài làm của nhóm em chưa có đủ dữ liệu này. Nếu có thể, chúng em cũng sẽ thêm Mutual Information và Principal Component vào trong việc phân tích dữ liệu

Machine Learning 
Tư duy về mô hình: Nếu bạn phải giải thích mô hình của mình cho một người 
không biết về Machine Learning, bạn sẽ mô tả nó như thế nào?
Câu trả lời: Mô hình của nhóm em là một mô hình học tập bởi máy thực hiện để dự đoán về giá nhà ở Việt Nam năm 2025 và truyền về kết quả và mô hình phân tích.
Thử nghiệm và điều chỉnh: Trong quá trình huấn luyện mô hình, bạn có từng thử 
nghiệm các siêu tham số khác nhau không? Nếu có, hãy mô tả một lần thử nghiệm 
và kết quả bạn thu được. 
Câu trả lời: Chúng em có cho phép mô hình học máy sử dụng các tham số khác nhau như learning_rate là 0.001 hoặc 0.01
activation là Relu hoặc tanh, hidden_layer_sizes là (64, 32) hoặc (128, 64) hoặc (256, 128, 64)
Cải tiến mô hình: Nếu mô hình của bạn chưa đạt hiệu suất như mong muốn, bạn 
sẽ làm gì để cải thiện? Hãy đề xuất ít nhất hai cách để nâng cao độ chính xác hoặc 
hiệu suất của mô hình. 
Câu trả lời: Để cải tiến mô hình, nhóm em sẽ thử thêm các models khác như XGBoost hoặc LightGBM, thêm việc lựa chọn các feature cho mô hình để loại bỏ các feature không cần thiết, sử dụng Hyperparameter tuning