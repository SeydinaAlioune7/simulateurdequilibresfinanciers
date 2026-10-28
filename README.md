# Simulateur d'Équilibres Financiers (EUREKA 2026)
### Action Logement Services · Direction des Financements Bailleurs et Collectivités (DFBC)

Outil web interactif d\'instruction financière et de modélisation prévisionnelle des opérations de logement social et résidences conventionnées (Résidences Sociales, Foyers, Pensions de Famille, Hébergement).

---

## 🏢 Structure et Fonctionnalités

1. **Données administratives & Juridiques**
   - Identification de l\'opération, nom de programme, référent et identifiants patrimoniaux / SAP.
   - Gestion multi-phases dynamique (Phase 1 · Démolition, Phase 2 · Construction Neuve, Phase 3 · Réhabilitation, Phase 4 · VEFA, Phase 5 · Hébergement).
   - Recalcul consolidé automatique des logements et surfaces à l\'échelle de l\'opération.

2. **Zonage & Périmètres Réglementaires**
   - Sélection des zones de loyers réglementaires (Zone I, Ibis, II, III).
   - Détection automatique de la Direction Régionale Action Logement compétente (ex: DE 01 Île-de-France, DE 04 AURA, etc.).
   - Qualification instantanée de l\'éligibilité au dispositif **Action Cœur de Ville (ACV)** et **ANRU/NPNRU**.

3. **Surfaces & Ratios d\'Efficience**
   - Calcul en direct du ratio d\'optimisation architecturale **SHAB / SDP** avec seuil d\'alerte et cible de performance ALS (≥ 80%).
   - Prise en compte de la durée d\'exonération légale de **TFPB**.

4. **Calendrier Opérationnel & Jalons Décisionnels**
   - Suivi des jalons clés : Dépôt PC, Obtention du PC purgé, Ordre de Service (OS) et Mise en Service (MES).
   - Détermination instantanée du premier jalon de livraison de l\'opération consolidée.

---

## 🚀 Déploiement Cloudflare Pages

Le projet est configuré pour un déploiement continu et direct sur **Cloudflare Pages** :

- **Framework preset :** None / Static HTML
- **Build command :** *(laisser vide)*
- **Build output directory :** / (racine)
- **Fichier principal :** index.html
