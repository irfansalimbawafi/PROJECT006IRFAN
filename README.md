Project 06 -- Simulasi Data Recovery

Langkah - langkah :
1) Jalankan Script : 1_setup_simulasi.bat, script ini akan membuat folder D:\SimulasiDrive_D berisi : 10 folder utama, Masing-masing 3 Subfolder, dan 180 file dummy dengan berbagai format.
2) Jalankan Script : 2_recovery_data.bat, script ini akan menyalin semua isi dari D:\SimulasiDrive_D ke C:\SimulasiDrive_C\DataRecovery_YYYYMMDD. File recovery_log.txt akan otomatis terbuat
3) Jalankan Script : 3_recovery_data_modifikasi.bat, fitur tambahan :  Hitung jumlah file sumber & backup otomatis, Backup hanya file .pdf dan .docx, Hasil Backup dikompres ke .zip
4) Verifikasi hasil dengan menjalankan perintah CMD: dir /a /s /b "D:\SimulasiDrive_D" | find /c /v "" , dir /a /s /b "C:\SimulasiDrive_C" | find /c /v ""
   
