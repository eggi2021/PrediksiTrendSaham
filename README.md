# PrediksiTrendSaham
File Algoritma Berisi Tentang Alur Algoritma dan Pengujian Tuning Parameter
File Pengujian Berisi Tentang Pengujian Cross Validation

List Tuning Parameter :
1. Jumlah Attribut Prediktor
2. Jumlah Decision Tree
3. Kedalaman Decision Tree
4. Jumlah Data

List Attribut Prediktor ( Technical Indicators ) :
1. Upper Band
2. Lower Band
3. Stochastic %K
4. Stochastic %D
5. Relative Strength Index
6. Simple Moving Average
7. Chaikin
8. On Balance Volume
9. Williams %R

Penjelasan Kelas :
Kelas 1 = Uptrend/Bullish Trend
Kelas 0 = Downtrend/Bearish Trend

Penentuan Kelas :
Kelas(n) = IF(Close(n - 1) >= Close(n - 2), Then Kelas = 1, Else Kelas = 0)

Dimana n adalah periode hari
