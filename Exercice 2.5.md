Variables
   a, b en Entier
Début
   a ← Lire("Entrez le premier nombre : ")
   b ← Lire("Entrez le deuxième nombre : ")
   Si a = 0 OU b = 0 Alors
      Écrire "Le produit est nul"
   SinonSi (a > 0 ET b > 0) OU (a < 0 ET b < 0) Alors
      Écrire "Le produit est positif"
   Sinon
      Écrire "Le produit est négatif"
   FinSi
Fin
