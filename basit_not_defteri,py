print("""****************
Not defterine hoş geldiniz

Yapabileceğiniz işlemler: 
"yaz" ile bir şeyler yazabilirsiniz 
"gör" ile bir not defterini görebilirsiniz
"sil" ile notlarınızı silebilirsiniz 
"çık" ile not defterinden çıkabilirsiniz\n
****************""")

liste = []

while True:
    islem = input("İslem giriniz\n>>> ")
    if islem == "yaz":
        yaz = input("Not defterine bir şeyler yazabilirsiniz \n>>> ")
        liste.append(yaz)
    elif islem == "gör":
        print('İşte not defterindeki içerikler:\n>>>', liste)
    elif islem == "sil":
        sil = input("Neyi silmek istiyorsunuz?\n>>> ")
        if sil in liste:
            liste.remove(sil)
        else:
            print("Silmek istediğiniz not bulunamadı.")
    elif islem == "çık":
        print("Çıkılıyor.....")
        break
    else:
        print("Lütfen doğru işlem giriniz.")
