**1 - Tout en parcourant – analysant l’application, lister rapidement sur un bloc-notes les défauts de qualité du code que vous identifiez sur cette application**
## `Application.java`
- Ajout de constantes :
```java
    // Ajouter une constante pour la nouvelle vitesse pour ne pas changer le code en dur
    moi.changerVitesse(maVoiture, 80);
    // ET
    moi.changerVitesse(maVoiture,30);
```

## `Conducteur.java`
- Ajout de constantes :
```java
    // Ajouter une constante pour l'âge adulte pour ne pas changer le code en dur
    public boolean estAdulte() {
        return age >= 10;
    }
```

## `Voiture.java`
- Ajout fonction `AfficherInfos` :
```java
    // Ajouter une fonction pour ne pas avoir de duplication de code
    System.out.println("Modèle : " + modele);
    System.out.println("Couleur : " + couleur);
    System.out.println("Vitesse actuelle : " + vitesse);
```
