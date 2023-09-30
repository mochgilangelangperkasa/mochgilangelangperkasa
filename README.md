import sys #memasukkan program sys ke dalam program
flag = 1 #ini merupakan perulangannya
while flag == 1: #jika perulangan yang di input itu flagnya 1 maka dia akan melakukan perulangannya
    print("------------------------------------------------") #menampilkan teks
print("Aplikasi Membuat Urutan Bilangan\n-------------------------") #menampilkan teks

nil1 = int(input("Silahkan masukkan nilai batas awal = ")) #pada baris ini merupakan variabel da nilai batas awalnya
nil2 = int(input("Silahkan masukkan nilai batas akhir = ")) #pada baris ini merupakan variabel da nilai batas awalnya

print("Anda ingin mengurutkan bilangan apa?: ") #menampilkan teks
print("1. Genap") #menampilkan teks
print("2. Ganjil") #menampilkan teks    pilihan = int(input("Silahkan masukkan pilihan anda: ")) # ini merupakan variabel dari menu mengurutkan bilangan

if pilihan == 1: #ini merupakan if atau percabangan jika menu yang di pilih adalah genap
        print("Hasilnya adalah: ") #menampilkan teks
        for i in range(nil1, nil2 + 1): #disini nilai dijelaskan bahwa i merupakan nil1 dan 2 yg telah di inputkan
            if i % 2 == 0: #pada baris ini i akan di bagi dengan 2 untuk menampilkanhasil nilainya
                print(i, end=' ') #menampilkan hasilnya
elif pilihan == 2:
        print("Hasilnya adalah: ") #menampilkan teks
        for i in range(nil1, nil2 + 1):  #disini nilai dijelaskan bahwa i merupakan nil1 dan 2 yg telah di inputkan
            if i % 2 == 1: #pada baris ini i akan di bagi dengan 2 untuk menampilkanhasil nilainya
                print(i, end=' ') #menampilkan hasilnya
else:
        print("Pilihan tidak valid. Silakan pilih 1 atau 2\n------------------------------") #menampilkan teks

cek =input("\n------------------------------\napakah kamu ingin mengulangi? (y/n): ") #ini merupakan variabel dari perulangan program-
if cek == 'y' or cek == 'Y': #jika yang di inputkan y atau Y 
        flag = 1 #maka akan dinyatakan menjadi flag=1
else:#dan jika bukan y atau Y yg di input akan mengakhiri program
        print(exit) #disini akan menampilkan teks dan
        sys.exit(0) #disini akan mengakhiri programnya
        print(i)
