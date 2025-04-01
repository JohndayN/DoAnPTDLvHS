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

Machine Learning 
Tư duy về mô hình: Nếu bạn phải giải thích mô hình của mình cho một người 
không biết về Machine Learning, bạn sẽ mô tả nó như thế nào?
Câu trả lời: Mô hình của nhóm em là một mô hình học tập bởi máy thực hiện để dự đoán về giá nhà ở Việt Nam năm 2025 và truyền về kết quả và mô hình phân tích.
Thử nghiệm và điều chỉnh: Trong quá trình huấn luyện mô hình, bạn có từng thử 
nghiệm các siêu tham số khác nhau không? Nếu có, hãy mô tả một lần thử nghiệm 
và kết quả bạn thu được. 
Câu trả lời: Chúng em chưa thử mô hình siêu tham số khác
Cải tiến mô hình: Nếu mô hình của bạn chưa đạt hiệu suất như mong muốn, bạn 
sẽ làm gì để cải thiện? Hãy đề xuất ít nhất hai cách để nâng cao độ chính xác hoặc 
hiệu suất của mô hình. 
Câu trả lời: Để cải tiến mô hình, nhóm em sẽ thử thêm các models khác như XGBoost hoặc LightGBM, thêm việc lựa chọn các feature cho mô hình để loại bỏ các feature không cần thiết, sử dụng Hyperparameter tuning