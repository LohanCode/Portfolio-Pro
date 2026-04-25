# 📝 Modifications apportées à stage_1.html

## 🎯 Objectif
Réorganiser le fichier `stage_1.html` pour adopter la même structure que `stage_2.html` :
- **Regrouper plusieurs compétences par thème/tâche** dans une même div
- **Utiliser toutes les images** (st1_1 à st1_9) **sans doublons**
- **Structure cohérente** entre les deux pages de stage

---

## 📊 Comparaison Avant / Après

### ❌ AVANT : 9 divs (1 compétence = 1 div)

| Div | Compétence | Image(s) |
|-----|------------|----------|
| 1 | Répondre aux incidents... | st1_4.jpg |
| 2 | Développer la présence en ligne | st1_2.jpg |
| 3 | Mettre à disposition... | st1_3.jpg |
| 4 | Répondre aux incidents... | st1_8.jpg |
| 5 | Mettre à disposition... | st1_9.jpg |
| 6 | Travailler en mode projet + Organiser son développement | st1_5.jpg |
| 7 | Développer la présence en ligne | st1_9.jpg ⚠️ doublon |
| 8 | Mettre à disposition... | st1_2.jpg ⚠️ doublon |
| 9 | Organiser son développement | st1_5.jpg ⚠️ doublon + st1_1.jpg |

**Problèmes identifiés :**
- 🔴 Images en double : st1_2, st1_5, st1_9
- 🔴 Images non utilisées : st1_6, st1_7
- 🔴 Compétences dispersées sur plusieurs divs

---

### ✅ APRÈS : 4 divs (plusieurs compétences regroupées par thème)

| Div | Titre | Compétences | Images |
|-----|-------|-------------|--------|
| 1 | Développement de nouvelles fonctionnalités métier | Répondre aux incidents... + Développer la présence en ligne + Mettre à disposition... | st1_2, st1_3, st1_4 |
| 2 | Maintenance évolutive d'une application web | Répondre aux incidents... + Mettre à disposition... | st1_8, st1_9 |
| 3 | Travail collaboratif et gestion de versions | Travailler en mode projet + Organiser son développement | st1_5, st1_6, st1_7 |
| 4 | Montée en compétences sur Symfony et outils professionnels | Développer la présence en ligne + Organiser son développement | st1_1 |

---

## 🖼️ Utilisation des images

| Image | Avant | Après |
|-------|-------|-------|
| st1_1.jpg | Div 9 | Div 4 ✅ |
| st1_2.jpg | Div 2 + Div 8 (doublon) | Div 1 ✅ |
| st1_3.jpg | Div 3 | Div 1 ✅ |
| st1_4.jpg | Div 1 | Div 1 ✅ |
| st1_5.jpg | Div 6 + Div 9 (doublon) | Div 3 ✅ |
| st1_6.jpg | ❌ Non utilisée | Div 3 ✅ |
| st1_7.jpg | ❌ Non utilisée | Div 3 ✅ |
| st1_8.jpg | Div 4 | Div 2 ✅ |
| st1_9.jpg | Div 5 + Div 7 (doublon) | Div 2 ✅ |

**Résultat :** Toutes les images sont maintenant utilisées exactement **une fois**.

---

## 📋 Détail des 4 nouvelles sections

### 1️⃣ Développement de nouvelles fonctionnalités métier sur une application web existante

**Compétences mises en œuvre :**
- Répondre aux incidents et aux demandes d'assistance et d'évolution
- Développer la présence en ligne de l'organisation
- Mettre à disposition des utilisateurs un service numérique

**Description :**
Suite à des demandes d'évolution fonctionnelle, j'ai modifié le modèle de données de l'application afin d'intégrer de nouveaux champs et fonctionnalités. J'ai également configuré l'interface d'administration pour permettre aux utilisateurs de gérer ces nouvelles fonctionnalités. Ces évolutions ont permis d'enrichir le service proposé et de renforcer la présence en ligne de l'organisation.

**Preuves :** st1_2.jpg, st1_3.jpg, st1_4.jpg

---

### 2️⃣ Maintenance évolutive d'une application web en environnement professionnel

**Compétences mises en œuvre :**
- Répondre aux incidents et aux demandes d'assistance et d'évolution
- Mettre à disposition des utilisateurs un service numérique

**Description :**
L'application étant déjà en production, j'ai participé à sa maintenance évolutive en réalisant des modifications sur des fonctionnalités existantes. Ces évolutions ont été intégrées directement dans l'interface de l'application pour que les utilisateurs puissent continuer à utiliser le service dans de bonnes conditions.

**Preuves :** st1_8.jpg, st1_9.jpg

---

### 3️⃣ Travail collaboratif et gestion de versions dans un projet de développement

**Compétences mises en œuvre :**
- Travailler en mode projet
- Organiser son développement professionnel

**Description :**
Le projet a été réalisé en collaboration avec l'équipe de développement. J'ai travaillé avec les autres membres du projet en utilisant des outils de gestion de versions (Git), des procédures de validation du code (pull requests) et des pipelines d'intégration continue. Cela m'a permis d'organiser mon travail et de respecter les bonnes pratiques professionnelles.

**Preuves :** st1_5.jpg, st1_6.jpg, st1_7.jpg

---

### 4️⃣ Montée en compétences sur Symfony et outils de développement professionnels

**Compétences mises en œuvre :**
- Développer la présence en ligne de l'organisation
- Organiser son développement professionnel

**Description :**
Au cours de mon stage, j'ai renforcé mes compétences sur le framework Symfony ainsi que sur les outils de développement utilisés en entreprise. L'application web développée a permis à l'organisation de gérer des contenus et contribue à sa présence en ligne.

**Preuves :** st1_1.jpg

---

## ✅ Avantages de la nouvelle structure

1. **Cohérence** avec stage_2.html
2. **Pas de doublons** d'images
3. **Toutes les images utilisées** (st1_1 à st1_9)
4. **Compétences regroupées logiquement** par thème
5. **Structure plus lisible** et professionnelle
6. **Moins de répétition** dans les contenus
