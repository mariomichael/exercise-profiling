## Test Plan Screenshot
`Before Optimize`
Test Plan 2
![cmd](https://github.com/mariomichael/exercise-profiling/blob/main/Image/student-name.png)
![Jmeter](https://github.com/mariomichael/exercise-profiling/blob/main/Image/result_name.png)
Test Plan 3
![cmd](https://github.com/mariomichael/exercise-profiling/blob/main/Image/highest-gpa.png)
![Jmeter](https://github.com/mariomichael/exercise-profiling/blob/main/Image/result_highest_gpa.png)

`After Optimize`
Test Plan 2
![cmd](https://github.com/mariomichael/exercise-profiling/blob/main/Image/student-name_AFTER.png)
![Jmeter](https://github.com/mariomichael/exercise-profiling/blob/main/Image/result_name_AFTER.png)
Test Plan 3
![cmd](https://github.com/mariomichael/exercise-profiling/blob/main/Image/highest-gpa_AFTER.png)
![Jmeter](https://github.com/mariomichael/exercise-profiling/blob/main/Image/result_highest_gpa_AFTER.png)

# Reflection 5
## 1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?
Perbedaan pendekatan performance testing menggunakan JMeter dan profiling dengan Intellij Profiler adalah evaluasi dengan JMeter lebih fokus ke simulasi beban untuk mengevaluasi kinerja secara keseluruhan, sedangkan profiler dengan Intellij Profiler lebih fokus ke profiling, dimana fokus lebih diarahkan ke tingkat kode untuk mengidentifikasi penghambat secara lebih teknikal dan spesifik. JMeter hanya menunjukkan keseluruhan time sample yang diberikan, sedangkan dengan profiler, pengguna bisa mengetahui berapa lama setiap bagian kode dijalankan secara lebih detail. Hal ini menjadikan profiler lebih berguna untuk mengidentifikasi permasalahan pada function tertentu. Setelah pengujian dengan profiler berhasil, barulah diuji lagi dengan JMeter untuk menentukan keseluruhan waktu kerjanya. 
## 2. How does the profiling process help you in identifying and understanding the weak points in your application?
Profiling sangat membantu saya mengidentifikasi dan memahami bagian lemah kode saya karena setiap bagian kode dan function, bahkan function bawaan dites waktu kerjanya. Dengan hal ini saya bisa mengidentifikasi mana bagian dari fungsi yang saya tulis yang memakan waktu lama, sehingga refactoring bisa difokuskan ke function-function yang memakan waktu lama tersebut. Dengan begitu overall impact dari setiap refactor bisa lebih terasa dan cepat.
## 3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?
Ya, IntelliJ Profiler efektif dalam membantu saya mengidentifikasi masalah. Ini karena saya tidak perlu menguji secara manual dan menebak kira-kira bagian mana yang kurang baik performancenya. Saya hanya perlu menerima hasil tes dan memperbaiki berdasarkan hasil tes yang diberikan IntelliJ Profiler.
## 4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?
Tantangan terbesar saya adalah menentukan apakah dengan tugas yang harus dikerjakan, function tersebut layak memakan waktu selama itu. Selain itu susah dalam mencari cara mengoptimize kode. Saya mengatasi masalah layak atau tidaknya dengan cara mencari saran di Google dan membandingkan dengan tugas serta run time function-function lain. Sedangkan saya mengatasi kesulitan mengoptimize kode adalah dengan terus berlatih untuk bisa membuat kode yang optimal dan memperbanyak membaca dokumentasi untuk mencari cara yang paling efisien.
## 5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?
Manfaat utama yang saya rasakan dengan menggunakan IntelliJ Profiler adalah banyak sekali fitur yang disediakan dengan berbagai data yang detail yang mempermudah saya untuk melakukan refaktor kode. Selain itu IntelliJ Profiler terintegrasi dengan IntelliJ Ultimate sehingga saya tidak perlu pindah-pindah Windows dan bisa mengidentifikasi kode langsung di software yang sama.
## 6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?
Cara saya menangani hal tersebut adalah dengan mencoba me-run ulang testing. Jika hasilnya masih berbeda dan jauh, saya akan mencoba menggunakan software testing lain dan membandingkan hasilnya dengan keduanya. Saya akan memilih 2 hasil yang paling konsisten dan mirip dari ketiga software testing. Namun jika perbedaannya tidak terlalu krusial, mungkin ada perbedaan environment lain yang mempengaruhi hal tersebut dan tidak akan terlalu menjadi masalah besar. Meskipun begitu saya akan coba menganalisis dan memperbaiki hingga perbedaannya tidak sebesar itu.
## 7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?
Strategi yang saya gunakan untuk mengoptimasi kode setelah testing adalah mengoptimasi kode yang menurut hasil testing memnakan waktu paling lama. Saya akan tetap memperhatikan aspek tugas yang function tersebut kerjakan dan waktu kerjanya. Saya memastikan perubahan yang saya lakukan tidak mengubah fungsionalitas kode adalah dengan membuat tes di awal seperti yang diajarkan Pak Ade lalu me-run test setiap melakukan perubahan pada kode, sehingga saya tahu apakah fungsionalitas aplikasi yang saya buat masih tetap sama atau berubah. Dengan begitu memaintain fungsionalitas aplikasi jadi lebih mudah.