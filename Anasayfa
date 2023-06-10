HalMeyve = ["Armut", "Elma", "Portakal"]
HalKgMeyve = [5, 2, 3]
HalSebze = ["Fasülye", "Havuç", "Biber"]
HalKgSebze = [3, 4, 5]
ManavAldığıMeyve = []
ManavinAldıgıMeyveKG = []
ManavAldığıSebze = []
ManavinAldıgıSebzeKG = []
MüşteriAldığıMeyve = []
MüşteriAldığıMeyveKG = []
MüşteriAldığıSebze = []
MüşteriAldıgıSebzeKG = []
Devam="t"
print("-------------------------Manav Halde--------------------------------")
while Devam=="t":
    a = int(input("""
    1-Meyve
    2-Sebze
    """))

    if a==1:
        print(HalMeyve)
        print(HalKgMeyve)
        if a==1:
            ManavinSececegiMeyve = int(input("""
            1-Armut
            2-Elma
            3-Portakal
            """))
            if ManavinSececegiMeyve == 1:
                while True:
                    ManavinAlacagiArmutKG = int(input("Kaç KG armut alacaksınız = "))
                    if ManavinAlacagiArmutKG <= HalKgMeyve[0]:
                        break
                    else:
                        print("Elimizde yeterli armut yok.")
                ManavAldığıMeyve.append("Armut")
                ManavinAldıgıMeyveKG.append(ManavinAlacagiArmutKG)
                Devam=input("Eğer t girersen Meyve ve Sebze Bölümüne geri dönebilirsin ama eğer manava almak istedikleriniz bittiyse t dışında herhangi bir harfe basın")

            elif ManavinSececegiMeyve == 2:
                while True:
                    ManavinAlacagiElmaKG = int(input("Kaç KG elma alacaksınız = "))
                    if ManavinAlacagiElmaKG <= HalKgMeyve[1]:
                        break
                    else:
                        print("Elimizde yeterli elma yok.")
                ManavAldığıMeyve.append("Elma")
                ManavinAldıgıMeyveKG.append(ManavinAlacagiElmaKG)
                Devam=input("Eğer t girersen Meyve ve Sebze Bölümüne geri dönebilirsin ama eğer manava almak istedikleriniz bittiyse t dışında herhangi bir harfe basın")

            elif ManavinSececegiMeyve == 3:
                while True:
                    ManavinAlacagiPortakalKG = int(input("Kaç KG portakal alacaksınız = "))
                    if ManavinAlacagiPortakalKG <= HalKgMeyve[2]:
                        break
                    else:
                        print("Elimizde yeterli portakal yok.")
                ManavAldığıMeyve.append("Portakal")
                ManavinAldıgıMeyveKG.append(ManavinAlacagiPortakalKG)
                Devam=input("Eğer t girersen Meyve ve Sebze Bölümüne geri dönebilirsin ama eğer manava almak istedikleriniz bittiyse t dışında herhangi bir harfe basın")
    elif a==2:
            ManavinSececegiSebze = int(input("""
            1-Fasülye
            2-Havuç
            3-Biber
            """))
            if ManavinSececegiSebze == 1:
                while True:
                    ManavinAlacagiFasulyeKG = int(input("Kaç KG fasulye alacaksınız = "))
                    if ManavinAlacagiFasulyeKG <= HalKgSebze[0]:
                        break
                    else:
                        print("Elimizde yeterli fasulye yok.")
                ManavAldığıSebze.append("Fasulye")
                ManavinAldıgıSebzeKG.append(ManavinAlacagiFasulyeKG)
                Devam=input("Eğer t girersen Meyve ve Sebze Bölümüne geri dönebilirsin ama eğer manava almak istedikleriniz bittiyse t dışında herhangi bir harfe basın")
            elif ManavinSececegiSebze == 2:
                while True:
                    ManavinAlacagiHavuçKG = int(input("Kaç KG havuç alacaksınız = "))
                    if ManavinAlacagiHavuçKG <= HalKgSebze[0]:
                        break
                    else:
                        print("Elimizde yeterli havuç yok.")
                ManavAldığıSebze.append("Havuç")
                ManavinAldıgıSebzeKG.append(ManavinAlacagiHavuçKG)
                Devam=input("Eğer t girersen Meyve ve Sebze Bölümüne geri dönebilirsin ama eğer manava almak istedikleriniz bittiyse t dışında herhangi bir harfe basın")
            elif ManavinSececegiSebze == 3:
                while True:
                    ManavinAlacagiBiberKG = int(input("Kaç KG Biber alacaksınız = "))
                    if ManavinAlacagiBiberKG <= HalKgSebze[0]:
                        break
                    else:
                        print("Elimizde yeterli biber yok.")
                ManavAldığıSebze.append("Biber")
                ManavinAldıgıSebzeKG.append(ManavinAlacagiBiberKG)
                Devam=input("Eğer t girersen Meyve ve Sebze Bölümüne geri dönebilirsin ama eğer manava almak istedikleriniz bittiyse t dışında herhangi bir harfe basın")
print("-------------------------------Müşteri Bölümü--------------------------------")
print("Manavdaki Aldığı Meyveler = ", ManavAldığıMeyve)
print("Manavdaki Aldığı Meyvelerin KG Değerleri", ManavinAldıgıMeyveKG)
print("Manavdaki Aldığı Sebzeler = ", ManavAldığıSebze)
print("Manavdaki Aldığı Sebzelerin KG Değerleri", ManavinAldıgıSebzeKG)
print("Lütfen Manavın Elindeki Ürünleri seçin")
devam1="t"
while devam1=="t":
    b = int(input("""
    1-Meyve
    2-Sebze
    """))
    if b == 1:
        print(ManavAldığıMeyve)
        print(ManavinAldıgıMeyveKG)
        MüşteriSeçeceğiMeyve = int(input("""
            1-Armut
            2-Elma
            3-Portakal
            """))
        if MüşteriSeçeceğiMeyve == 1:
                while True:
                    MüşteriAlacagiArmutKG = int(input("Kaç KG armut alacaksınız = "))
                    if MüşteriAlacagiArmutKG <= ManavinAlacagiArmutKG:
                        break
                    else:
                        print("Elimizde yeterli armut yok.")
                MüşteriAldığıMeyve.append("Armut")
                MüşteriAldığıMeyveKG.append(MüşteriAlacagiArmutKG)
                devam1=input("Eğer t girersen Meyve ve Sebze Bölümüne geri dönebilirsin ama eğer manava almak istedikleriniz bittiyse t dışında herhangi bir harfe basın")
        if MüşteriSeçeceğiMeyve == 2:
                while True:
                    MüşteriAlacagiElmaKG = int(input("Kaç KG Elma alacaksınız = "))
                    if MüşteriAlacagiElmaKG <= ManavinAlacagiElmaKG:
                        break
                    else:
                        print("Elimizde yeterli Elma yok.")
                MüşteriAldığıMeyve.append("Elma")
                MüşteriAldığıMeyveKG.append(MüşteriAlacagiElmaKG)
                devam1=input("Eğer t girersen Meyve ve Sebze Bölümüne geri dönebilirsin ama eğer manava almak istedikleriniz bittiyse t dışında herhangi bir harfe basın")
        if MüşteriSeçeceğiMeyve == 3:
                while True:
                    MüşteriAlacagiPortakalKG = int(input("Kaç KG Portakal alacaksınız = "))
                    if MüşteriAlacagiPortakalKG <= ManavinAlacagiPortakalKG:
                        break
                    else:
                        print("Elimizde yeterli Portakal yok.")
                MüşteriAldığıMeyve.append("Portakal")
                MüşteriAldığıMeyveKG.append(MüşteriAlacagiPortakalKG)
                devam1=input("Eğer t girersen Meyve ve Sebze Bölümüne geri dönebilirsin ama eğer manava almak istedikleriniz bittiyse t dışında herhangi bir harfe basın")
    elif b==2:
        print(ManavAldığıSebze)
        print(ManavinAldıgıSebzeKG)
        if 2==2:
            MüşteriSeçeceğiSebze = int(input("""
            1-Fasülye
            2-Havuç
            3-Biber
            """))
            if MüşteriSeçeceğiSebze == 1:
                    while True:
                        MüşteriAlacagiFasülyeKG = int(input("Kaç KG Fasülye alacaksınız = "))
                        if MüşteriAlacagiFasülyeKG <= ManavinAlacagiFasulyeKG:
                            break
                        else:
                            print("Elimizde yeterli Fasülye yok.")
                    MüşteriAldığıSebze.append("Fasülye")
                    MüşteriAldıgıSebzeKG.append(MüşteriAlacagiFasülyeKG)
                    devam1 = input("Eğer t girersen Meyve ve Sebze Bölümüne geri dönebilirsin ama eğer manava almak istedikleriniz bittiyse t dışında herhangi bir harfe basın")
            if MüşteriSeçeceğiSebze == 2:
                    while True:
                        MüşteriAlacagiHavuçKG = int(input("Kaç KG Havuç alacaksınız = "))
                        if MüşteriAlacagiHavuçKG <= ManavinAlacagiHavuçKG:
                            break
                        else:
                            print("Elimizde yeterli Havuç yok.")
                    MüşteriAldığıSebze.append("Havuç")
                    MüşteriAldıgıSebzeKG.append(MüşteriAlacagiHavuçKG)
                    devam1 = input("Eğer t girersen Meyve ve Sebze Bölümüne geri dönebilirsin ama eğer manava almak istedikleriniz bittiyse t dışında herhangi bir harfe basın")
            if MüşteriSeçeceğiSebze == 3:
                    while True:
                        MüşteriAlacagiBiberKG = int(input("Kaç KG Biber alacaksınız = "))
                        if MüşteriAlacagiBiberKG <= ManavinAlacagiBiberKG:
                            break
                        else:
                            print("Elimizde yeterli Biber yok.")
                    MüşteriAldığıSebze.append("Biber")
                    MüşteriAldıgıSebzeKG.append(MüşteriAlacagiBiberKG)
                    devam1=input("Eğer t girersen Meyve ve Sebze Bölümüne geri dönebilirsin ama eğer manava almak istedikleriniz bittiyse t dışında herhangi bir harfe basın")
        print("Müşterinin Aldığı Sebzeler = ",MüşteriAldığıSebze)
        print("Müşterinin Aldığı Sebzelerin KG Değerleri = ", MüşteriAldıgıSebzeKG)
        print("Müşterinin Aldığı Meyveler = ",MüşteriAldığıMeyve)
        print("Müşterinin Aldığı Meyvelerin KG Değerleri = ", MüşteriAldığıMeyveKG)
