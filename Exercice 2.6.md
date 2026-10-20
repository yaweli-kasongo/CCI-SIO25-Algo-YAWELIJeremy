Variable
   age en Entier
Début
   age ← Lire("Entrez l'âge de l'enfant : ")
   Si age >= 12 Alors
      Écrire "Cadet"
   SinonSi age >= 10 Alors
      Écrire "Minime"
   SinonSi age >= 8 Alors
      Écrire "Pupille"
   SinonSi age >= 6 Alors
      Écrire "Poussin"
   Sinon
      Écrire "Trop jeune pour une catégorie"
   FinSi
Fin
