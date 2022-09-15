Tập dữ liệu được lấy từ: https://www.kaggle.com/competitions/digit-recognizer/data

Các tệp dữ liệu train.csv và test.csv chứa hình ảnh thang màu xám của các chữ số vẽ tay, từ 0 đến 9.

Mỗi hình ảnh có chiều cao 28 pixel và chiều rộng 28 pixel, tổng cộng là 784 pixel. Mỗi pixel có một giá trị pixel duy nhất được liên kết với nó, cho biết độ sáng hoặc tối của pixel đó, với các con số cao hơn có nghĩa là tối hơn. Giá trị pixel này là một số nguyên từ 0 đến 255, bao gồm cả.

Tập train.csv có 785 cột. Trong đó cột đầu tiên là nhãn và phần còn lại của các cột chứa các giá trị pixel của hình ảnh được liên kết.
Bao gồm các tập dữ liệu train.csv, testdata.csv, và digittrain.csv, digittrain.csv là file lấy 10% từ tập train.csv để chọn ra siêu tham số cho mô hình. file train.csv để học sau khi có siêu tham sô và file test.csv ta dự đoán nhãn của file này.

Trong file submit bao gồm 2 file:
knnperdictqh.csv và rf_thaibao.csv là 2 file dự đoán từ tập test.csv để nộp lên kaggle.