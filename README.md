# ScoreCardCustomer
Project Bootscamp dibimbing DS 17 dengan topik Scorecard Customer untuk top up limit creditcard, data diperoleh dari kaggle dengan skillset: 
- Logistic Regression
- Gradient Boosting
- Weigh of Evidence (WOE)
- Information Value (IV)
- Binning
- Chi-Square Binning

# Feature
![image](https://user-images.githubusercontent.com/129568189/230429770-837c052b-85f2-4db7-b3a3-c264fc72bdb4.png)

# Feature Binning 
![image](https://user-images.githubusercontent.com/129568189/230429894-995c8f51-cd30-476c-9f0e-8e2b751497fa.png)

# Gradient Boosting Decision Trees
![image](https://user-images.githubusercontent.com/129568189/230430031-bbcae13e-2f8c-476c-82cf-4c7c64fa10c3.png)

#Logistic Regression vs Gradient Boosting Decision Trees
![image](https://user-images.githubusercontent.com/129568189/230430144-336caf99-23c3-4425-bcd8-15fcbaead789.png)

#Threshold Tunning
![image](https://user-images.githubusercontent.com/129568189/230430282-41faf91b-bcfc-4903-88c7-066aa5fd52c7.png)

# Kesimpulan
  - Nasabah terbanyak ada pada level 6 sebesar 35.12% dengan category Good Credit
  - Good Customer tertinggi: pada Level 6, 7, 5 dengan masing-masing rate (38.57%, 20.05%, 13.11%)
  - Default_Rate tertinggi: pada level 6, 3, 2, dengan masing-masing rate (22.97%, 15.79%, 14.77%)
  - Secara keseluruhan, jika kita memberikan top up limit maka kita akan mengalami kerugian sebesar 22.12%
  - Kita bisa memberikan top up limit pada level 7 karena Good_Rate dan Defautl_Rate berbeda signifikan
  - Hanya saja perlu diperhatikan kembali pada level 6 (Good Category) tapi menyumbang kerugian tertinggi. 
    Berarti ada feature yang berpengaruh tinggi yang tidak masuk pada data history customer .kita perlu 
    menambahkan beberapa feature Kembali pada data set selanjutnya.

![image](https://user-images.githubusercontent.com/129568189/230428949-2ab0b228-cd3e-41c9-9bd1-83ef692fe431.png)
