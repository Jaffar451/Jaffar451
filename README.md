- 👋 Hi, I’m @Jaffar451
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Jaffar451/Jaffar451 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
class Produit:
    def __init__(self, nom, prix, quantite):
        self.nom = nom
        self.prix = prix
        self.quantite = quantite

class Inventaire:
    def __init__(self):
        self.liste_produits = []

    def ajouter_produit(self, produit):
        self.liste_produits.append(produit)

    def afficher_inventaire(self):
        for produit in self.liste_produits:
            print(f"Produit: {produit.nom}, Prix: {produit.prix}, Quantité: {produit.quantite}")

# Création de produits
produit1 = Produit("Smartphone", 599, 10)
produit2 = Produit("Ordinateur portable", 1299, 5)

# Création de l'inventaire
inventaire = Inventaire()

# Ajout de produits à l'inventaire
inventaire.ajouter_produit(produit1)
inventaire.ajouter_produit(produit2)

# Affichage de l'inventaire
inventaire.afficher_inventaire()
