# 📚 BibliothequeApp — Application Android

Application mobile Android développée dans le cadre des Labs Android.
Elle permet de gérer une bibliothèque municipale : afficher, ajouter, modifier et supprimer des livres.

---

## 🔧 Technologies utilisées

- Java
- Android SDK
- RecyclerView
- CardView
- Room (SQLite)
- Material Design (FloatingActionButton, AlertDialog)
- Intent & Navigation entre Activities

---

## 📋 Labs réalisés

### Lab 4 — Affichage d'une liste de livres avec RecyclerView
- Création de la classe métier `Livre.java`
- Affichage d'une liste de livres avec `RecyclerView`
- Adapter personnalisé `LivreAdapter.java`
- Cartes avec badge de disponibilité vert/rouge

### Lab 5 — Navigation entre écrans et fiche détail
- Création de `DetailActivity`
- Navigation avec `Intent`
- Passage d'objets entre activités avec `Serializable`
- Bouton retour fonctionnel

### Lab 6 — Formulaire d'ajout et de modification
- Création de `AddEditActivity` avec formulaire
- Validation des champs avec `setError()`
- `FloatingActionButton` pour ajouter un livre
- Clic long pour modifier un livre
- Mode ajout et mode modification réutilisables

### Lab 7 — Persistance locale avec Room
- Transformation de `Livre.java` en entité `@Entity`
- Création de `LivreDao.java` avec `@Insert`, `@Update`, `@Delete`, `@Query`
- Création de `AppDatabase.java` avec singleton thread-safe
- Opérations en arrière-plan avec `ExecutorService`
- Suppression avec confirmation `AlertDialog`
- Message affiché quand la liste est vide

---

## 🚀 Comment lancer le projet

1. Cloner le repository : git clone https://github.com/Lad716-mikh/BibliothequeApp.git
2. Ouvrir le projet dans **Android Studio**
3. Lancer sur un émulateur ou un téléphone Android (API 24+)

---

## 🏷️ Tags Git

| Tag | Description |
|-----|-------------|
| `lab4` | Affichage liste RecyclerView |
| `lab4-v1.1` | Bonus : design amélioré |
| `lab5` | Navigation et fiche détail |
| `lab5-v1.1` | Bonus : design fiche détail |
| `lab6` | Formulaire ajout/modification |
| `lab6-v1.1` | Bonus : Toast, bouton Modifier |
| `lab7` | Persistance Room |
| `lab7-v1.1` | Bonus : message liste vide |

---

## 👨‍💻 Auteur

Mikhael — Étudiant en développement mobile Android