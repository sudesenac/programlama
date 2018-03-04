# programlama
#soru1

     def gelirHesapla(): 
    x=int(input("finansman gelirini giriniz:"))
    y=int(input("pazar gelirini giriniz:"))
    z=int(input("kira gelirini giriniz:"))
    gelir=(x+y+z)
    return gelir

    def giderHesapla():
    a=int(input("finanman giderini yazınız:"))
    b=int(input("ücreti giriniz:"))
    c=int(input("pazar giderini giriniz:"))
    d=int(input("kira giderini giriniz:"))
    e=int(input("muhasebe giderini giriniz:"))
    gider=(a+b+c+d+e)
    return gider

     x=int(input("finansman gelirini giriniz:"))
    y=int(input("pazar gelirini giriniz:"))
    z=int(input("kira gelirini giriniz:"))
    a=int(input("finanman giderini yazınız:"))
    b=int(input("ücreti giriniz:"))
    c=int(input("pazar giderini giriniz:"))
    d=int(input("kira giderini giriniz:"))
    e=int(input("muhasebe giderini giriniz:"))
    k=(x+y+z)-(a+b+c+d+e)
    if(int(k)>1000):
      print("işletme kar elde etmiştir.")
    elif(int(k)<1000):
      print("işletme zarar elde etmiştir.")
    else:
      print ("işletme ne kar ne zarar etmiştir.")


#soru2

#Kullanılabilirlik: (Planlanmış üretim süresi – Plansız Duruş) / Planlanmış Üretim Süresi
#Performans: (Standart Çevrim Zamanı x Üretim Miktarı) / (Planlanmış üretim süresi – Plansız Duruş)
#Kalite: Sağlam Ürün Miktarı / Toplam Üretim Mitarı
#OEE: Kullanılabilirlik x Performans x Kalite x %100

    def kullanilabilirlikHesapla():
    a=int(input("planlanmış üretim süresini giriniz:"))
    b=int(input("plansız duruşu giriniz:"))
    c=int(input("planlanmış üretim süresini giriniz:"))
    kullanilabilirlik=((a-b)/c)
    return kullanilabilirlik

    def performansHesapla():
    d=int(input("standart çevrimiçi zamanı giriniz:"))
    e=int(input("üretim miktarını giriniz:"))
    f=int(input("planlanmış üretim süresini giriniz:"))
    g=int(input("plansız duruşu giriniz:"))
    performans=((d*e)/(f-g))
    return performans

    def kaliteHesapla():
    h=int(input("sağlam ürün miktarını giriniz:"))
    j=int(input("toplam ürün miktarını giriniz"))
    kalite=(h/j)
    return kalite

    def oeeHesapla():
    k=int(input("kullanılabilirlik giriniz:"))
    z=int(input("performans giriniz:"))
    m=int(input("kalite giriniz:"))
    oee=((k*z*m)*100/100)
    return oee


#soru3
#Ciro: Satış Miktarı x Birim Satış Fiyatı
#Adambaşı Ciro: Toplam Ciro / Toplam Çalışan Sayısı

    def ciro():
    a=int(input("satış miktarı giriniz:"))
    b=int(input("birim satış fiyatı giriniz:"))
    ciro=a*b
    return ciro
    def adambasiCiro ():
    x=int(input("toplam giro giriniz:"))
    c=int(input("toplam çalışan sayısını giriniz:"))
    adambasiCiro=(x/c)
    return adambasiCiro
