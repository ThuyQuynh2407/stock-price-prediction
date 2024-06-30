# Stock Price Prediction of FPT
Dự đoán giá cổ phiếu FPT sử dụng LSTM

## Giới thiệu
Dự đoán giá cổ phiếu là bài toán liên quan đến chuỗi thời gian nhằm phân tích các số liệu thống kê về các quá trình đã diễn ra và được ghi chép theo khoảng thời gian nối tiếp nhau với mục tiêu sử dụng kinh nghiệm thu được trong quá khứ để dự báo tình hình xảy ra trong tương lai.

## Dữ liệu
Dữ liệu được CÔNG TY CỔ PHẦN ĐẦU TƯ FINPROS cung cấp gồm 97406 hàng và 8 cột (Ticker, Date/Time, Open, High, Low, Close, Volume, Open Interest)

## Yêu cầu bào toán
- Xây dựng một số mô hình dự đoán biến động giá cổ phiếu.
- Biến động giá cổ phiếu = Giá cổ phiếu N (phút hoặc giờ hoặc ngày) sau - Giá cổ phiếu hiện tại.
