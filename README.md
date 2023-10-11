# Bank_Marketing_Campaign
Pada project ini, kami melakukan analisis data serta pemodelan machine learning menggunakan dataset Bank Marketing Campaign di Portugal pada tahun 2014. Dataset tersebut berisikan informasi mengenai menerima atau tidaknya nasabah terhadap produk deposito di suatu bank setelah bank tersebut melakukan kampanye dengan cara telemarketing. Permasalahan pada final project ini adalah pada saat melakukan kampanye dengan cara telemarketing tentunya akan memakan waktu dan biaya yang sangat besar jika perusahaan tidak melakukan filter terhadap nasabah yang akan dihubungi. Oleh karena itu dibutuhkan efisiensi pada kampanye agar bank mendapatkan deposit sebanyak-banyaknya dengan biaya dan waktu sekecil mungkin. Pada project ini kami akan membantu perusahaan menekan biaya kampanye dengan cara memahami karakteristik dari nasabah yang berpotensi untuk melakukan term deposit, selain itu pada project ini kami juga berusaha menerapkan pemodelan machine learning untuk membantu dalam pengklasifikasian nasabah yang akan term deposit dan nasabah yang tidak akan term deposit. Project ini terbagi menjadi 7 bagian penting, yaitu :

1. Business Understanding : Pada bagian ini berisikan penjelasan mengenai permasalahan bisnis yang akan diselesaikan, tujuan dilakukan nya analisis data dan pemodelan machine learning, pendekatan analisis yang akan dilakukan, serta menjelaskan metric yang akan digunakan.

2. Data Understanding and Cleaning : Pada bagian ini berisikan penjelasan mengenai setiap kolom yang ada pada dataset, data cleaning untuk analisis, serta pembuatan kolom baru yang akan digunakan pada bagian data analisis.

3. Exploratory Data Analysis : Pada bagian ini berisikan hasil data analisis terkait distribusi data dan korelasi data dari setiap kolom, hasil data analisis mengenai conversion rate setiap fitur terhadap target(deposit/tidak deposit), serta rekomendasi yang didapatkan setelah melakukan analisis data.

4. Data Preprocessing for Machine Learning : Pada bagian ini berisikan data cleaning untuk pemodelan machine learning, pendefinisian feature (X) dan target (y), data splitting, pendefinisian encoder, pendefinisian scaler, serta pendefinisian resampler.

5. Modelling and Hyperparameter Tuning : Pada bagian ini berisikan pendefinisian metric yang akan digunakan, penentuan model-model mana saja yang akan dituning dari hasil cross-validation, hyperparameter tuning untuk mendapatkan model dan parameter terbaik yang akan dijadikan final model, serta analisis features importances dan analisis shap dari final model yang terpilih.

6. Probability and Financial Analysis : Pada bagian ini berisikan analisis terkait kelas probabilitas terhadap akurasi hasil prediksi serta analisis keuangan final.

7. Conclusion and Recommendation : Pada bagian ini berisikan kesimpulan dan rekomendasi baik dari hasil analisis data maupun hasil pemodelan machine learning.

Selain itu, kami juga mendeploy hasil pemodelan dengan bantuan streamlit sebagaimana berikut :

1. Positive Prediction

![positive prediction](https://github.com/1997Theo/Bank_Marketing_Campaign/assets/134950701/34fcab00-9562-4ffc-8851-5761058ba722)


2. Negative Prediction

![negativeprediction](https://github.com/1997Theo/Bank_Marketing_Campaign/assets/134950701/507d66f9-7667-4507-86ea-1c23fd1bcfb7)


Hasil streamlit dapat diakses melalui link berikut :

https://github.com/1997Theo/streamlit_bank_campaign

Visualisasi tambahan dari project berupa story tableau dan dashboard tableau dapat diakses melalui link berikut :

https://public.tableau.com/app/profile/linmar.theodorus.yohannes.sirait/viz/Final_Project_Tableau_Bank_Marketing_Campaign/DashboardKarakteristikNasabahBankPortugalUntukMelakukanTermDeposit?publish=yes
