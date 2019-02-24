% ### TRMAYOR CEP TELEFONU UYGULAMASI PYTHON 3.6 KODU
class telefon():
    def __init__(self,mesaj,arama,kamera,marka,model):
        self.mesaj=mesaj
        self.arama=arama
        self.kamera=kamera
        self.marka=marka
        self.model=model
        self.rehberekle=[]
        def kamera_ozl(self):
            if self.kamera==True:
                print('20mp kamera var kullanabilirsin.')
        def mesaj_at(self):
            if self.mesaj==True:
                b=input('mesajını gir')
                print(b,'mesajınız gönderiliyor')
            else:
                print('mesaj özelliğiniz yok')
        def rehber_ekle(self,numara):
            for num in self.rehber:
                if num==numara :
                    print('zaten ekli')
                else:
                    self.rehberekle.append(numara)
        def rehber_goster (self) :
            print(self.rehberekle)
        def arama_ozl(self):
            if self.arama==True:
                a=input('arayacağınız numarayı giriniz')
                print(a,'aranıyor...')
            else:
                print('arama özelliği bulunmamakta')
        def bilgileri_goster(self):
            print(self.mesaj,self.arama,self.kamera,self.marka,self.model)
