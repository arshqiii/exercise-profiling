# Tutorial Modul 5
Nama  : Muhammad Radhiya Arshq

NPM   : 2306275885

Kelas : ADPRO A

---

## Refleksi
> 1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?

Perbedaan dapat dilihat dari segi skala/tujuan yang berbeda, JMeter dapat digunakan untuk menguji performa aplikasi secara keseluruhan (dari perspektif user), sedangkan Profiller pada Intellij dapat digunakan mengoptimalkan performa kode secara spesifik.

> 2. How does the profiling process help you in identifying and understanding the weak points in your application?

Profilling membantu saya dalam mengidentifikasi dan mengenal weak points pada aplikasi dengan mengukur pemakaian CPU sehingga dapat mengidentifikasi metode atau fungsi mana yang memakan banyak waktu eksekusi, mengidentifikasi heap memory usage yang terlalu besar atau tidak efisien, dan lainnya.

> 3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?

Iya, karena penggunaannya tidak memerlukan alat eksternal tambahan karena terintegrasi langsung dengan IntelliJ IDEA, lalu saya bisa melihat performa aplikasi langsung saat berjalan melalui visualisasi yang intuitif

> 4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?

Beberapa tantangan yang saya hadapi ketika melakukan performance testing dan profilling adalah mementukan solusi optimisasi untuk method-method yang menggunakan banyak waktu

> 5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?

Main Benefit dari menggunakan Intellij Profiler dalam profilling adalah dapat mendeteksi bottleneck dengan cepat, mencegah memory leaks, dapat memperbaiki deadlocks & optimasi thread performance, dan tidak perlu third party akses karena langsung terintegrasi dengan Intellij IDEA

> 6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?

Untuk saat ini tidak pernah terjadi situasi dimana hasil Intellij dan Jmeter berbeda, namun jika terjadi maka saya akan coba gunakan keduanya bersama-sama untuk mendapatkan gambaran lengkap dan melakukan optimasi dengan efektif.

> 7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?

Strategi yang saya gunakan adalah memanfaatkan built-in features yang disediakan Java seperti stream, function untuk iterate list, dan lainnya yang bisa lebih baik dibanding penggunaan for loop biasa.


## Hasil JMeter from CMD
#### `/all-student`
![WhatsApp Image 2025-03-13 at 11 31 41_cd464b45](https://github.com/user-attachments/assets/386e1783-7211-4b54-8f2a-e2fd0779ca62)

#### `/all-student-name`
![WhatsApp Image 2025-03-13 at 11 34 00_d5879323](https://github.com/user-attachments/assets/ae0e0b1a-d05c-4faa-a9b7-e2119bf6b46a)

#### `/highest-gpa`
![WhatsApp Image 2025-03-13 at 11 31 30_8bff7306](https://github.com/user-attachments/assets/591d4f93-7153-41a4-946b-a0009b6baebf)

## Hasil endpoint `/all-student`

### Before Optimization
![image](https://github.com/user-attachments/assets/9b3363b8-6bb7-493f-a561-c56f36fcff94)

### After Optimization
![image](https://github.com/user-attachments/assets/93f6b74e-bc12-4b49-9140-79f5c5b18101)


## Hasil endpoint `/all-student-name`

### Before Optimization
![WhatsApp Image 2025-03-13 at 08 57 23_282ec37c](https://github.com/user-attachments/assets/e3f9dae7-8db0-464f-8d37-97db3e889fbc)

### After Optimization
![image](https://github.com/user-attachments/assets/081fac91-5abc-4c22-9e57-2e5572f63b3d)


## Hasil endpoint `/highest-gpa`

### Before Optimization
![WhatsApp Image 2025-03-13 at 08 59 36_377384d2](https://github.com/user-attachments/assets/bb37228c-a526-42ab-ba50-e917ed66062e)

### After Optimization
![image](https://github.com/user-attachments/assets/5f8df29c-2839-4504-8c50-3a8bc81fea82)


