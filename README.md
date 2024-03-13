## - Screenshots -

### Before Profiling

/all-student :
![all-student](/images/allStudent_before.png)

/all-student-name :
![all-student-name](/images/studentName_before.png)

/highest-gpa :
![highet-gpa](/images/gpa_before.png)

### After Profiling

/all-student :
![all-student](/images/allStudent_after.png)

/all-student-name :
![all-student-name](/images/studentName_after.png)

/highest-gpa :
![highet-gpa](/images/gpa_after.png)

## - Reflection- 

1. What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?
   Testing dengan JMeter bertujuan untuk menganalisis performance aplikasi secara umum, sedangkan profiling dengan IntelliJ bertujuan untuk menganalisis performance aplikasi secara lebih detail. Dengan IntelliJ, kita dapat mengidentifikasi performance tiap method pada aplikasi secara detail, sehingga kita dapat mengetahui bagian aplikasi mana yang perlu dioptimasi. Sedangkan dengan JMeter, informasi yang kita dapatkan tidak sedetail hasil profiling pada IntelliJ, kita tidak mendapatkan hasil performance dari bagian-bagian kecil aplikasi seperti method.
<br>
<br>

2. How does the profiling process help you in identifying and understanding the weak points in your application?
   Hasil profiling menunjukkan informasi runtime untuk tiap method pada aplikasi sehingga kita dapat mengetahui method mana yang memiliki runtime paling tinggi. Kita jadi tahu, method mana yang perlu dioptimasi agar runtimenya menurun.
   <br>
   <br>
3. Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?
   Ya.
   <br>
   <br>
4. What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?
   Salah satu tantangan yang saya hadapi adalah ketidaktahuan atau rasa tidak familiar terhadap tools testing dan profiling pada tutorial ini, yaitu JMeter dan IntelliJ profiling. Saya menghadapinya dengan mencoba mempelajari cara menggunakan keduanya dengan bertanya kepada teman yang sudah lebih familiar dengan tools tersebut, serta "mencoba-coba" sendiri fitur yang disediakan pada tools.
   <br>
   <br>
5. What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?
   Salah satu manfaat terbesarnya adalah saya jadi lebih mudah mengidentifikasikan bagian dari aplikasi yang perlu dioptimasi berdasarkan informasi terkait performance aplikasi seperti CPU time.
   <br>
   <br>
6. How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?
   Saya mencoba me re-run aplikasinya dan mengulang proses profiling beberapa kali untuk memastikan bahwa inkonsistensi tersebut memang selalu terjadi dan bukan hanya kebetulan satu kali. Apabila inkonsistensi tersebut memang selalu terjadi, saya akan coba memeriksa dan memahami kriteria profiling tiap tool. Kemungkinan perbedaan kriteria tersebut memang menyebabkan perbedaan hasil profiling.
   <br>
   <br>
7. What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?
   Saya mencoba memahami tujuan dari kode tersebut, kemudian memodifikasinya (seperti misalnya memodifikasi algortima kode agar lebih efisien) supaya runtime-nya menurun. Modifikasi tersebut dilakukan sesuai dengan fungsionalitas awal dari kode. Setelah memodifikasi, saya kembali menjalankan kode tersebut dan memeriksa outputnya, memastikan bahwa outputnya sama dengan output awal agar tahu pasti bahwa fungsionalitas kodenya tidak berubah.