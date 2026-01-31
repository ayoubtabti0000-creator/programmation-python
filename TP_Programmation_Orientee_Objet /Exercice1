class Produit:
    def __init__(self,reference,designation,prix_achat,prix_vente,quantite):
        self.__reference=reference
        self.__designation=designation
        self.__prix_achat=prix_achat
        self.__prix_vente=prix_vente
        self.__quantite=quantite
    @property
    def reference(self):
        return self.__reference
    @property
    def designation(self):
        return 
    def afficher_infos(self) :
        print(f"référence: " , self.__reference )
        print(f"designation:",self.__designation)
        print(f"prix d'achat :",self.__prix_achat)
        print(f"prix d'vente :",self.__prix_vente)
        print(f"Quantite actuel :",self.__quantite)
    def modifier_prix_achat(self,nvprix) :
        if nvprix > 0 :
            self.__prix_achat=nvprix
        else:
            print("Le prix d'achat doit être positif")
    def modifier_prix_vente(self,nvprix) :
        if nvprix > 0 :
            self.__prix_vente=nvprix
        else:
            print("Le prix d'achat doit être positif")

    def modifier_quantite(self, valeur):
        if self.__quantite + valeur >= 0:
            self.__quantite += valeur
        else:
            print("Stock insuffisant.")


p1 = Produit("REF123", "Smartphone XYZ", 300, 500, 30)

p1.modifier_prix_achat(350)
p1.modifier_prix_vente(600)
p1.modifier_quantite(10)
print("\nAprès modifications :")
p1.afficher_infos()
