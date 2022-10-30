# merge-projesi-patika.dev

# SORU 1
## Yukarıdaki dizinin sort türüne göre aşamalarını yazınız?
* 			16	21	11	8	12	22			Dizinin normal şekli
      16	21	11			8	12	22	  Diziyi bölüp yeniden yazıyoruz
    16	21		11			8		12	22	Diziyi üçlü olarak şekillendiriyoruz
16		21		11			8		12		22 Her biri tek olacak şekide yazıyoruz

* Bölme işlemimizi bitirdik. Şimdi ise bir grup tekrar sıralı bir şekilde birleştirmemiz gerekiyor.
* 
İkili sıralanarakdik.   16	21		11			8	12		22		
Üçlü grup getirip sıraladık.			11	16	21			8	12	22		
Son birleştirmeyle dizimizi elde ettik.				8	11	12	16	21	22	

# SORU 2
##  Big-O'yu gönderin.
* Merge Sort bir Böl ve Fethet (Böl ve Yönet Algoritması) işlemidir. Big-O gösterimi ise O(nlogn) dir. Sebebi ise tekrar tekrar test edilir.
