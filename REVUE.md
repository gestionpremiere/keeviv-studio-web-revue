# Keeviv Studio Web — revue visuelle

Captures du 30 octobre 2026, code local, branche `feature/studio-web-platform`.

Rien ici n’est une session staging authentifiée. Rien n’a été publié.

Deux sources :

- **LOCAL_FIXTURE** — éditeur Pages dans le harnais admin (`apercu-studio.html`). Les cours (Pilates, Yoga, Plateau) sont des données de démonstration.
- **LOCAL_PUBLIC_RENDERER** — vrai composant public `StudioSite`, route `/site/plateau`, avec un JSON local. Ce n’est pas `studios.keeviv.com`.

Le bouton **Sections** est dans le flux, au-dessus du canevas. Il ne flotte plus sur l’horaire. « Brouillon » est le statut de la page. « Toujours au menu » veut dire que l’accueil reste dans le menu public.

## Pages — téléphone

LOCAL_FIXTURE. Le titre « Studio Plateau » est entier. Le bouton Sections est au-dessus du canevas.

### 320 × 568

![Pages 320](pages-320.png)

### 360 × 740

![Pages 360](pages-360.png)

### 390 × 844

![Pages 390](pages-390.png)

### 430 × 932

![Pages 430](pages-430.png)

## Feuille Sections

LOCAL_FIXTURE. La feuille reste au-dessus du rail. Elle défile toute seule.

### 320 × 568

![Sections 320](sections-320.png)

### 390 × 844

![Sections 390](sections-390.png)

## Éditeur de section

LOCAL_FIXTURE. Redimensionnement du viewport, pas un clavier physique. Le titre focalisé reste au-dessus du rail, y compris à 320 × 420.

### 320 × 420

![Éditeur 320 par 420](editeur-320x420.png)

### 320 × 568

![Éditeur 320 par 568](editeur-320x568.png)

### 390 × 844

![Éditeur 390 par 844](editeur-390x844.png)

## Horaire dans l’éditeur

LOCAL_FIXTURE. Sous 500 px de canevas, chaque cours est une pile : nom, jour et heure, durée, lieu, disponibilité réelle. À 768 et 1440, le tableau reste en ligne. À 1024, le canevas de la colonne est étroit, donc l’horaire se pile ; la composition deux colonnes de Pages reste en place.

### 320

![Horaire éditeur 320](horaire-editeur-320.png)

### 390

![Horaire éditeur 390](horaire-editeur-390.png)

### 430

![Horaire éditeur 430](horaire-editeur-430.png)

### 768

![Horaire éditeur 768](horaire-editeur-768.png)

### 1024

![Horaire éditeur 1024](horaire-editeur-1024.png)

### 1440

![Horaire éditeur 1440](horaire-editeur-1440.png)

## Pages — tablette et bureau

LOCAL_FIXTURE. Rail à gauche. 768 et 820 sont empilés. 1024 et 1440 sont en deux colonnes.

### 768

![Pages 768](pages-768.png)

### 820

![Pages 820](pages-820.png)

### 1024

![Pages 1024](pages-1024.png)

### 1440

![Pages 1440](pages-1440.png)

## Horaire public

LOCAL_PUBLIC_RENDERER. Même présentation que l’éditeur sur téléphone : cartes empilées à 320, 390 et 430. Tableau à 768, 1024 et 1440, parce que la page publique utilise toute la largeur. Le compte membre (horaire Keeviv de l’application) n’est pas cette page.

### 320

![Horaire public 320](public-horaire-320.png)

### 390

![Horaire public 390](public-horaire-390.png)

### 430

![Horaire public 430](public-horaire-430.png)

### 768

![Horaire public 768](public-horaire-768.png)

### 1024

![Horaire public 1024](public-horaire-1024.png)

### 1440

![Horaire public 1440](public-horaire-1440.png)
