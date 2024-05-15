# Proyek Semi-Supervised Learning dengan LabelPropagation, LabelSpreading, SelfTrainingClassifier, dan Co-Training

## Deskripsi

Proyek ini bertujuan untuk menerapkan metode-metode semi-supervised learning, yaitu LabelPropagation, LabelSpreading, SelfTrainingClassifier, dan Co-Training. Metode semi-supervised learning memanfaatkan data yang memiliki label sebagian untuk melakukan pembelajaran, sehingga dapat menghasilkan model yang lebih baik daripada pembelajaran hanya dengan data berlabel penuh.

### Metode yang Digunakan

1. **LabelPropagation**: Metode ini mengusulkan label untuk sampel yang tidak berlabel berdasarkan kesamaan dengan sampel yang berlabel.

2. **LabelSpreading**: Metode ini juga menggunakan kesamaan antara sampel untuk mengusulkan label untuk sampel yang tidak berlabel, tetapi dengan pendekatan yang sedikit berbeda dari LabelPropagation.

3. **SelfTrainingClassifier**: Metode ini melatih model dengan data berlabel penuh dan kemudian menggunakan model tersebut untuk memprediksi label pada data yang tidak berlabel. Prediksi yang dianggap meyakinkan kemudian ditambahkan ke data berlabel, dan proses ini diulangi secara iteratif.

4. **Co-Training**: Metode ini melibatkan dua model yang bekerja pada dua set fitur yang berbeda. Model-model tersebut saling bertukar informasi dengan memperbarui label data berlabel baru dengan menggunakan prediksi dari model lain.
