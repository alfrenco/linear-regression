[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=8372165&assignment_repo_type=AssignmentRepo)


## Dataset 

Dataset yang akan digunakan berasal dari https://www.kaggle.com/brllrb/uber-and-lyft-dataset-boston-ma
Dataset tersebut berisi data Uber and Lyft di Boston, MA


## Objectives 

Membuat model Regression menggunakan Linear Regression untuk memprediksi harga perjalanan platform ride-hailing dengan dataset yang disediakan.


## Kesimpulan

Saya membuat 2 model menggunakan Linear Regression biasa dan Linear Regression dengan Polynomial Feature Derajat-2 dimana hasil evaluasi untuk Train-Set, Test-Set, dan juga Inference-Set cukup bagus karena nilai Mean Absolute Error (MAE) cukup kecil dan nilai R2 Score cukup tinggi. **Linear Regression biasa** pada **Test-Set** mendapatkan nilai **MAE 1.751 dan R2 Score 0.93** sedangkan pada **Inference-Set** mendapatkan nilai **MAE 2.597 dan R2 Score 0.83**. **Linear Regression dengan Polynomial Feature Derajat-2** pada **Test-set** mendapatkan nilai **MAE 1.302 dan R2 Score 0.96** sedangkan pada **Inference-Set** mendapatkan nilai **MAE 1.752 dan R2 Score 0.91.**

Jadi dari kedua model yang dibuat, model yang memiliki performa lebih baik adalah **Linear Regression dengan Polynomial Feature Derajat-2**.

