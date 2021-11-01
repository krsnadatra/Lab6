# Sourcecode-Materi6PercabangandanPerulanganKompleks
#JoshuaWanggai-71200671  
#https://dh3di.blogspot.com/2018/08/algoritma-percabangan-bertingkat.html  

''' input 
avanza = b.sewa 300k &amp; b.asuransi 15k 
xenia = b.sewa 300k &amp; b.asuransi 15k 
innova = b.sewa 500k &amp; b.asuransi 25k 
alphard = b.sewa 750k &amp;b.asuransi 30k  

proses: (biayasewa * lamapenyewaan) + biaya asuransi  

output = hasil perhitungan daripada proses tersebut 
''' 

jenismobil = input("masukkan jenis mobil : ") 
penyewaan = int(input("masukkan lama hari penyewaan : "))  
if jenismobil == "avanza":     
biayaSewa = 300000     
biayaAsuransi = 15000 
elif jenismobil == "xenia":     
biayaSewa = 300000     
biayaAsuransi = 15000 
elif jenismobil == "innova":     biayaSewa = 500000     biayaAsuransi = 25000 
else:     jenismobil == "alphard"     biayaSewa = 750000     biayaAsuransi = 30000  
TotalHarga = (biayaSewa * penyewaan ) + biayaAsuransi print(TotalHarga)
