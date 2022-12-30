# UasMpr6
Nama kelompok :
Farrel Dwi Prayogo 201401119
Susi Susanti Telambanua 201401125
Tema Aplikasi : Task List
Tujuan Aplikasi : mencatat Tugas Tugas penting Seperti Notepad

tampilan Sign in dinggunakan untuk login ke aplikasi ,sebelum masuk ke main pages kami membuat sebuah fragment Signinfragment.kt dinggunakan untuk mendata users yang memakai aplikasi dengan koneksi firebase real time dan kami enable autenfication on apabila belum mendaftar akan muncul check point your password wrong maka dianjurkan untuk mendaftar
![image](https://user-images.githubusercontent.com/102476391/210109020-1cb76644-888c-4ead-b567-00c0ae95efa6.png)


Tampilan Sign Up Dinggunakan untuk Mendaftar ke aplikasi dengan Fragment signupfragment.kt 
![image](https://user-images.githubusercontent.com/102476391/210108744-426a37e1-bac5-4afc-9971-c5354a681202.png)

Tampilan main pages menu utama ketika sudah login maka langsung di direct dan sistem akan melakukan pengecekan sesuai dengan algoritma navigationbar.xml yg sudah dibuat
dibawah ini adalah proses menambah data val todoTask = binding.todoEt.text.toString()
            if (todoTask.isNotEmpty()){
                if (toDoData == null){
                    listener?.saveTask(todoTask , binding.todoEt)
                    jika data sama dengan 0 maka isi data yang kosong maka ketika button di tekan dia akan langsung mengsave task tersbut 
![image](https://user-images.githubusercontent.com/102476391/210109399-4448f527-30e4-4e08-9043-586cf4aa740b.png)

Tampilan Data Update Masih sama di satu fragment activity yg sama 
}else{
![image](https://user-images.githubusercontent.com/102476391/210109878-1591ace6-39ff-4a40-9ae2-62045d87fecf.png)

Tampilan Data Hapus
![image](https://user-images.githubusercontent.com/102476391/210109983-42705658-1a0c-4628-a7d5-a354f05692c8.png)
