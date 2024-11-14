# Linux
Bu projede en çok kullanılan windows komutlarına yer verilmiştir.

## Klasör Komutları

#### `CD` Komutu
Bu komut klasöre girmek için kullanılır.<br>
>Kullanım Şekli: cd  Klasör_Adı
```
cd kerim
```
![cd](https://github.com/user-attachments/assets/fd8981c1-21de-4146-831e-cb06f345cebd)
>[!WARNING]
>Klasör adı yazarken klasörün adını hatasız yazının büyük harf küçük harf uyumuna dikkat ediniz.

#### `DİR` Komutu
Bu komut terminalin konumundaki dosyanın içerisinde bulunan şeyleri listeler.<br>
>Kullanım Şekli : dir
```
dir
```
![dir](https://github.com/user-attachments/assets/b1ff0022-2490-42b4-b304-35bc216e018c)

#### `MKDİR` Komutu
Bu komut klosör içerisinde yeni bir klasör açmak için kullanılır.<br>
>Kullanım Şekli: mkdir Klasör_Adı
```
mkdir windows_komutları
```
![mkdir](https://github.com/user-attachments/assets/4fe6a490-10a2-4cae-a52f-16e7ab92a767)

>[!TIP]
>CD ile dosyaya girerken <ins>Tab</ins> tuşu ile son kaydedilen belge adını anında yazabilirsiniz.

#### `TOUCH` Komutu 
Bu komut yeni bir belge oluşturmaya yarar.<br>
>Kullanım Şekli : touch belgeadı
```
touch yeni.txt
```
![touch](https://github.com/user-attachments/assets/f31cbdee-2268-44f5-8622-25b337c9fde6)

#### `ECHO` Komutu
Bu komut belgenin içerisine yazı yazmaya yarar.<br>
>Kullanım Şekli : echo yazı > dosyaadı
```
echo merhaba dunya > yeniisim
```
![echo](https://github.com/user-attachments/assets/c803e100-ee6c-4f66-ad13-ef398d857fe1)

>[!TIP]
>İşlem çıktısı aşağıdaki gibidir.

>![çıktı](https://github.com/user-attachments/assets/42976bcf-7fc6-4b08-beea-bd9b5cfc4f77)

#### `REMOVE` Komutu
Bu komut silme işlemine yarar.<br>
>Kullanım Şekli : rm dosyaadı
```
rm yeni.txt
```
![dosyasilme](https://github.com/user-attachments/assets/51fd210d-0533-4fa0-98ab-114f7660dae4)

>[!TIP]
>Silme işlemi dosya için ayrı klasör için ayrı uygulanır.
>Klasör için olanı alttaki gibidir.

>Kullanım Şekli : rm -r klasöradı
```
rm -r yenidosya
```
![klasörsilme](https://github.com/user-attachments/assets/88b1f733-31ca-444a-bcb9-62dea475f525)

#### `MOVE` Komutu
Bu komut belgenin veya klasörün adını değiştirmeye yarar.<br>
>Kullanım şekli : mv dosyaadı yenidosyaadı
```
move yenikalsör yenbiisim
```
![isim değişme](https://github.com/user-attachments/assets/7bb7173d-512b-4644-8eb0-5c2d8770b2e5)

#### `ALIAS` Komutu
Bu komut uzun ve sık kullandığımız komutları kısaltmak için kullanılır.<br>
>Kullanım Şekli : alias yenideğer = "atanacakdeğer"
```
alias ml = "echo \"merhaba dunya \""
ml
```
![alias](https://github.com/user-attachments/assets/559cbfda-522f-4f6e-a487-4a799849f6d8)

>[!NOTE]
>Bu komut daha çok programlamadaki değişken tanımlamaya benzer ml ye değer ataması yapıyoruz.

#### `HEAD` Komutu
Bu komut dosyanın ilk satırlarını getirmeye yarar.<br>
>Kullanım Şekli : head -n getireceksatırsayısı dosyaadı
```
head -n 5 yeniisim
```
![head](https://github.com/user-attachments/assets/6c14fc65-79bb-4ba9-8cf7-6a9198bf06fe)

>[!NOTE]
>Bu komutta getirmesini istediğimiz satır sayısını yazmazsak varsayılan olarak ilk 10 satırı getirir.<br>

#### `TAIL` Komutu
Bu komut dosyanın son satırlarını getirmeye yarar.<br>
>Kullanım Şekli : tail -n getireceksatırsayısı dosyaadı
```
tail -n 4 yeniisim
```
![tail](https://github.com/user-attachments/assets/a39d184a-ee98-42ea-aa0a-f095b9cb91a7)

>[!NOTE]
>Bu komutta getirmesini istediğimiz satır sayısını yazmazsak varsayılan olarak son 10 satırı getirir.

#### `HISTORY` Komutu
Bu komut linuxta kullanılan komutların hepsini listeler.<br>
>Kullanım Şekli : history
```
history
```
![history](https://github.com/user-attachments/assets/10213e10-fa81-408b-874b-5196ce4ef91e)

>[!NOTE]
>Bu komutta;
>```
>history 5
>```
>yaparak son 5 komutu görüntüleriz bu değişkenlik gösterebilir.

#### `GREP` Komutu
Bu komut belirli bir kalıbı filtrelemek ve o kalıbı içeren tüm satırları görüntülemek için kullanılır.
>Kullanım Şekli : grep -i "bulunacakmetin" dosyaadı
```
grep -i "i" yeniisim
```
![grep](https://github.com/user-attachments/assets/8f116571-0db8-4e9f-b103-ff64ca4c16d0)

>[!NOTE]
>```
>grep --help
>```
>Grep komutunun kullanımı hakkında bilgi verir.
>```
>-i
>```
>Büyük/Küçük harf uyumuna dikkat etmeksizin arama yapar.
>```
>grep -in
>```
>Ek olarak bulunan ifadenin hangi satırda olduğunu da gösterir.

