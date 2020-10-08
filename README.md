# Manipulation_Pandas_Project
Training Project after learn Manipulation with pandas 

Studi Kasus 1

Project dari Andra
Berikut adalah isi email yang ditugaskan oleh Andra:

 

Diberikan dataset ‘retail_raw_test.csv’

1 Baca dataset
2 Tipe data diubah menjadi tipe yang seharusnya
   - customer_id dari string ke int64,
   - quantity dari string ke int64,
   - item_price dari string ke int64
3. transform product_value supaya bentuknya seragam dengan format PXXXX, assign ke kolom baru "product_id", dan drop kolom "product_value", jika terdapat nan gantilah dengan "unknown".
4. tranform order_date menjadi value dengan format YYYY-mm-dd
5. cek data hilang dari tiap kolom dan kemudian isi missing value
  di brand dengan "no_brand", dan
6. cek dulu bagaimana missing value di city & province - isi missing value di city dan province dengan "unknown"
7. create column city/province dari gabungan city & province
8. membuat index berdasarkan city_provice, order_date, customer_id, order_id, product_id (cek index)
9. membuat kolom "total_price" sebagai hasil perkalian quantity dengan item_price
10. slice data hanya untuk Jan 2019


