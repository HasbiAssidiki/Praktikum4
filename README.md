# Pertemuan 7 - Kondisional dan perulangan  
**Praktikum 2 - Modul Praktikum 2**  
Program sederhana dengan input tiga buah bilangan, dari ketiga bilangan tersebut tampilkan bilangan terbesarnya.

1. Cetak nilai bilangan 1 sampai 3 yang akan di input   
> a = int(input("Masukan Bilangan 1 : "))  
> b = int(input("Masukan Bilangan 2 : "))  
> c = int(input("Masukan Bilangan 3 : "))  

2. Lalu buat kondisi if dan cetak hasil maksimal `maks` seperti dibawah ini.  
Masukan a sebagai nilai maksimal, lalu masukan jika b adalah nilai maksimal maka b akan di cetak sebagai nilai terbesar begitu juga dengan c  
> `%d` digunakan sebagai pengganti untuk nilai numerik atau desimal.    
> maks = a  
> if b > maks:  
>     maks = b  
> if c > maks:  
>     maks = c  
    
> print()  
> print('Nilai yang terbesar adalah : %d' % maks)  
3. Run program dengan 3 kondisi inputan yang berbeda  

![Screenshot (27)](https://user-images.githubusercontent.com/115614317/200729501-00b8da93-c112-4805-b807-45961d20dbb0.png)

--------------------------------------------------------------------------------------------
Flowchart Praktikum 2 - Modul 2  
-------------------------------
**Latihan 1 - Modul Praktikum 3**  

Membuat program bilangan acak yang lebih kecil dari 0.5  

1. Cetak nilai bilangan yang akan di input  
2. Gunakan fungsi `import random` terlebih dahulu  
> jumlah = int(input("Masukkan nilai n : "))  
> import random  
> for i in range (jumlah) :  
>    print("Data ke", i+1,"=",(random.uniform(0.1,0.5)))  

3. Angka yang di input akan mencetak jumlah seberapa banyaknya nilai data ke `print("Data ke", i+1,"=",(random.uniform(0.1,0.5)))`  
4. Cetak dengan rumus `i+1` untuk melakukan peningkatan nilai `+1` setiap banyaknya nilai input yang dimasukkan  
> (0.1,0.5) gunanya untuk membatasi angka acak dari 0,1 sampai 0,5  
5. Jalankan program  

![image](https://user-images.githubusercontent.com/115614317/200731070-f2ec85ee-66eb-407e-a2fa-32b7d7630d6a.png)  

-----------------------------------------------------------------------------------------------------------------
Latihan 2 - Modul Praktikum 3  
-----------------------------
Program menampilkan bilangan terbesar dari n buah data yang diinputkan dan masukkan angka 0 untuk berhenti  
> max = 0  
> while True:  
>    a=int(input("Masukan bilangan : "))  
>    if max < a:  
>        max = a  
>    if a ==0 :  
>        break  
>  
> print()  
> print("Bilangan terbesar adalah :", max)  
