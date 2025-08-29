# Terraform Hello World Lab

## Tujuan
Mendeploy EC2 secara otomatis menggunakan Terraform, dengan Apache HTTP server yang menampilkan halaman HTML 'Hello World'.

## Langkah-langkah
1. Buat EC2 instance menggunakan Terraform.
2. Buat Security Group yang mengizinkan HTTP (80) dan SSH (22).
3. Gunakan user_data untuk:
   - Install Apache ()
   - Pull file HTML dari repository Git
4. Output public IP untuk diakses di browser.

