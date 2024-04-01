# Open Recruitement Admin KCV 2024

## Deskripsi Tugas
Buatlah model untuk memprediksi salary berdasarkan data-data lowongan pekerjaan yang sudah tersedia pada file train.csv. Skor akhir berdasarkan metrik evaluasi RMSE. Untuk contoh submisi dapat dilihat di file sample_submission.csv.

Penjelasan dataset:
- File [_train.csv_](/resources/train.csv) berisi data yang dapat digunakan peserta untuk melatih model Machine Learning dengan delimiter berupa pipe “|”.
- File [_predict-case.csv_](/resources/predict_case.csv) berisi data yang dapat digunakan peserta untuk menguji model yang dibuat dengan delimiter berupa pipe “|”.
- File [_sample_submission.csv_](/resources/sample_submission.csv) adalah contoh bentuk submisi yang benar.

Penjelasan kolom:

- ```job_title``` = nama pekerjaan
- ```location``` = lokasi perusahaan tempat bekerja
- ```salary_currency``` = mata uang dari salary
- ```career_level``` = tingkat jabatan dari pekerjaan yang ditawarkan
- ```experience_level``` = lama pengalaman pelamar yang diminta perusahaan
- ```education_level``` = syarat tingkat pendidikan bagi pelamar pekerjaan
- ```employment_type``` = tipe kontrak
- ```job_function``` = kategorisasi jenis pekerjaan
- ```job_benefits``` = manfaat yang bisa diberikan perusahaan
- ```company_process_time``` = rata-rata lama waktu perusahaan untuk merespon pelamar
- ```company_size``` = jumlah karyawan yang bekerja di perusahaan tersebut
- ```company_industry``` = jenis industri yang menjadi lini bisnis perusahaan
- ```job_description``` = deskripsi pekerjaan yang ditawarkan
- ```salary``` = jumlah gaji yang ditawarkan setiap bulan

## Evaluasi Tugas
The submission will be evaluated using MSE Metrik from the actual value.

The public leadearboard just cover 70% of test data, there are still 30% hidden data for final scoring

## Format Submisi
For each ID in the test set, you must predict the SALARY. The file should contain a header and have the following format:
```
id,salary
1022,12345
1023,54321
1024,333
etc.
```