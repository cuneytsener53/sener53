from colorama import Fore
print("\t","="*10,"HOŞGELDİNİZ","="*10)

print("""\nYAPABİLECEĞİNİZ ŞEYLER
      

      1/>Bu veritabanında kaç okul izleniyor?\n
      2/>Kaç okulda ilişkili test bilgisi yok?\n
      3/>Hangi okullar genel olarak en iyi puana sahiptir?\n
      4/>Hangi okullar matematik ve eleştirel okuma arasında en farklı puanlara sahiptir?\n
      5/>Matematik ortalaması en iyi olan okullar ?\n
      
                                                                                          """)
x =input("Ne bulmak istiyorsunuz?\t:")

while True:
    if x == "1":
        print("Bu veritabanında kaç okul izleniyor?\n")
        dosyadı = "pro.Okulsayısı.txt" #Burada dosyamız var 
        infile = open(dosyadı, 'r') #Dosyayı açıyoruz
        lines = 0
        words = 0
        characters = 0
        for line in infile:
            wordslist = line.split()
            lines = lines + 1 #Her satır geçtiğinde bir eklersek satır sayısını buluruz her satırda 1 okul olduğuna göre okul sayısını bulmuş oluruz.
        print("Bu veri tabanında toplam {} tane okul izleniyor!".format(lines))
        input()
        break
    
    elif x  == "2" :
        print("Kaç okulda ilişkili test bilgisi yok?\n")
        fname = "testolmayan.txt" #Burada dosyamız var 
        infile = open(fname, 'r') #Dosyayı açıyoruz
        lines = 0
        words = 0
        characters = 0
        for line in infile:
            wordslist = line.split()
            lines = lines + 1 #Her satır geçtiğinde bir eklersek satır sayısını buluruz her satırda 1 okul olduğuna göre okul sayısını bulmuş oluruz.
        print("Teste tabi tutulmayan {} tane okul var!".format(lines))
        input()
        break    
    elif x == "3" :
        print("Hangi okullar genel olarak en iyi puana sahiptir?\n")
        file = open("eniyiler.txt","r") # Dosyayı okuma kipiyle açıyoruz. Türkçe karaktere dikkat.
 
        for i in file: # Tıpkı listeler gibi dosyanın her bir satırı üzerinde geziniyoruz.
            print(i) # Her bir satırı ekrana basıyoruz.
        file.close()
        print(Fore.GREEN,"En iyiler şu şekilde hesaplanıyor")
        print("""
#####################################                  
Okul numarası  
Okul adı 
Mezun olan öğrenci sayısı 
Matematik ortalaması         >400 !  X  
Eleştiriel okuma ortalaması  >400 !  Y
toplam öğrenci sayısı           
EĞER X > 400 VE Y >400 EN İYİLER OLUR
#####################################                               """)
        input()
        break
            
    if x == "4":
        print("Hangi okullar matematik ve eleştirel okuma arasında en farklı puanlara sahiptir\n")
        file = open("Farkıfazlaolanlar.txt","r") # Dosyayı okuma kipiyle açıyoruz. Türkçe karaktere dikkat.
 
        for i in file: # Tıpkı listeler gibi dosyanın her bir satırı üzerinde geziniyoruz.
            print(i) # Her bir satırı ekrana basıyoruz.
        file.close()
        print(Fore.RED,"Fark şu şekilde hesaplanıyor")
        print("""
#####################################                  
Okul numarası  
Okul adı 
Mezun olan öğrenci sayısı 
Matematik ortalaması         >x   
Eleştiriel okuma ortalaması  >y
toplam öğrenci sayısı           

x - y = z           
eğer z >=50     farkı fazla olur
#####################################                      """)
    input()
    break
    
    elif x == "5":
        print("Matematik ortalaması en iyi olan okullar ?\n")
        file = open("iyimat.txt","r") # Dosyayı okuma kipiyle açıyoruz. Türkçe karaktere dikkat.
 
        for i in file: # Tıpkı listeler gibi dosyanın her bir satırı üzerinde geziniyoruz.
           print(i) # Her bir satırı ekrana basıyoruz.
        file.close()
        print("Matematik yükseklik derecesi nasıl ölçülüyor")
        print("""
#####################################                  
Okul numarası  
Okul adı 
Mezun olan öğrenci sayısı 
Matematik ortalaması         >x   
Eleştiriel okuma ortalaması  
toplam öğrenci sayısı           

#eğer x >=550 ise Matematik ortalaması yüksektir!5
#####################################                      """)

         
        
