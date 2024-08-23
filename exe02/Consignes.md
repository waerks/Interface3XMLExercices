# 1 # Tous les contenus de type STRING doivent avoir au minimum 2 caractères

# 2 # Tous les contenus du NOM, PRENOM, NUMERO (adresse) doivent avoir au maximum 16 caractères

# 3 # Tous les contenus du RUE, VILLE, PAYS doivent avoir "Belgique" et l'élément est optionnel

# 4 # Tous les contenus du GENRE doivent avoir une énumération de donnés
    - Femme
    - Homme
    - Non-binaire
    - Fluide
    - Autre

# 5 # Tous les contenus du CODE POSTAL doivent accepter seulement des entiers compris entre 1000 et 9999

# 6 # Tous les contenus des NUMEROS (téléphone) doivent utiliser si possible les regex pour soit :
    - commencer avec un + suivi de chiffres
    - uniquement avec des chiffres

# 7 # Tous les contenus des EMAILS doivent utiliser si possible les regex pour :
    valider la présence d'un @ au milieu de la donnée

# 8 # L'attribut TYPE de NUMERO sera une énumération :
    - domicile
    - bureau
    - mobile
    - autre

# 9 # L'attribut TYPE de EMAIL sera une énumération :
    - domicile
    - professionnel
    - promotionnel
    - autre

# # Une PERSONNE n'est pas obligée d'avoir une ADRESSE POSTALE, un TELEPHONE ou un EMAIL mais ne peut avoir qu'une seule ADRESSE POSTALE