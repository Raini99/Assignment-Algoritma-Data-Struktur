Algorithm & Data Structures - Technical Assignment


1.  Thermometer

	Kamu adalah seorang mahasiswa IT yang baru memulai perjalanan, kemudian kamu juga sudah belajar tentang adanya 
pseudocode. Kemudian dosenmu memmberikan sebuah tugas untuk membuat sebuah pseudocode tentang cara kerja sebuah 
thermometer yang akan merubah semua jenis suhu menjadi celcius.
Berikut adalah 3 cara konversi suhu ke dalam celcius:
fahrenheit to celcius = (N - 32) * (5/9)
kelvin to celcius = (N - 273.15)
celcius to celcius = N
 
Algoritma
 
Mulai
Inputkan  jenis suhu yang akan di konversi ke celcius (fahrenheit, kelvin atau celcius)
Masukkan atau inputkan nilai suhu (N)
Pilih nilai inputan 
Celcius
Kelvin
Fahrenheit
Jenis Suhu inputan celcius? Jika Ya, Inputkan a. Maka nilai N = N.
Jenis suhu inputan kelvin? Jika Ya, inputkan b. Maka kurangi N dengan 273.15
Jenis suhu inputan fahrenheit? Jika Ya, inputkan c. Maka kurangi terlebih dahulu nilai N dengan 32, kemudian kalikan dengan 5/9
Nilai keluaran dalam bentuk celsius.
Selesai
 
 
 
Psedoucode
STORE N as Integer in any value
STORE jenissuhu as string with any value
STORE result as integer
If ( jenissuhu equal celcius )
CALCULATE (N)
SET result with calculation result
Else If (jenissuhu = kelvin)
CALCULATE N - 273.15
SET result with calculation result
Else If (jenissuhu = fahrenheit)
	CALCULATE  (N - 32) * (5/9)
SET result with calculation result
END if
DISPLAY result
 

2.  Fizz-buzz 

    Write a program that prints the numbers from 1 to n
for multiples of 3 print "Fizz" instead of the number
for the multiples of 5 print "Buzz" instead of the number
for numbers which are multiplies of both 3 and 5 print "FizzBuzz"
for numbers not divisible by, 3, 5, or both, print the number as is
 
 
Psedoucode
STORE N with any number
STORE i with 0
While i less than N
	STORE currentValue with i plus 1
	IF (currentValue modulus by 3 equal 0)
		DISPLAY “Fizz”
	IF (currentValue modulus by 5 equal 0)
		DISPLAY “Buzz”
	IF (currentValue modulus by 3 equal 0 and currentValue modulus 
by 5 equal 0)
DISPLAY fizzbuzz
	ELSE 
		DISPLAY currentValue
	END if
	SET i with i plus 1
END WHILE
 
	
 
 
 
3.	Palindrome
    Buatlah sebuah program untuk mengecek apakah 1 buah nilai bersifat 
palindrome. Jika iya program akan mengembalikan status TRUE jika tidak 
program akan mengembalikan status FALSE.
Input hanya dapat menerima tipe data berupa string/teks.
 
STORE “input” with any STRING 
	STORE “palindrom”
	FOR	“input” FROM “input” index “input” length -1 TO “input”
	SET “palindrom” WITH “palindrom” CONCAT WITH “input” index “input”
	END FOR
 
	IF “input” is equal “palindrom”
	DISPLAY “TRUE”
	ELSE 
	DISPLAY “FALSE”
	END IF
 
 
4.	Skilvul ingin memberikan penilaian terhadap siswa
Setiap siswa akan menerima penilaian skala 0 - 100
Nilai di bawah 70 dianggap tidak lulus
Dalam memberikan nilai ada 2 tahapan penting yaitu:
Untuk proses pembulatan nilai kelipatan 5, syaratnya adalah nilai tersebut harus kurang/lebih kecil dari 3 jaraknya dengan nilai pembulatan ke atas.
Jika nilai kurang dari 68, tidak dapat melakukan pembulatan karena tetap dianggap tidak lulus.
Input berupa Nilai Awal
Output berupa Nilai Akhir baik yang dapat dilakukan pembulatan ataupun 
tidak
 
 
STORE originalGrade as integer in any value
STORE result as integer
Let finalGrade equal 0
IF (originalGrade < 68) 
	finalGrade equal originalGrade
	CALCULATE result with calculation result
ELSE
	IF (originalGrade modulus by 5 equal 0)
	finalGrade equal originalGrade
	CALCULATE result with calculation result
ELSE
	IF ((originalGrade plus  1) modulus by 5 equal 0)
	finalGrade equal originalGrade plus 1
	CALCULATE result with calculation result
 
ELSE IF ((originalGrade plus  2) modulus by 5 equal 0)
	finalGrade equal originalGrade
	CALCULATE result with calculation result
ELSE
	FinalGrade equal originalGrade
DISPLAY result
END IF.
 
 
	
	
