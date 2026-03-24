#  Projet Infrastructure Réseau — TechSolutions SARL

## 📋 Description
Déploiement d'une infrastructure réseau multiservice complète 
simulée sous GNS3, réalisé dans le cadre de la formation 
ingénieure à ESPRIT.

## 🏗️ Architecture
- **Backbone** : 5 routeurs interconnectés (R1, R2, R3, R4, R5)
- **4 départements** : Web/Marketing, IT/Supervision, 
  Base de données, Partage de fichiers
- **Routage dynamique** : OSPF sur toute l'infrastructure
- **Accès Internet** : NAT via R-Internet

## 🛠️ Technologies utilisées
| Technologie | Usage |
|---|---|
| GNS3 + VMware | Simulation réseau |
| Cisco IOS | Configuration routeurs |
| OSPF | Routage dynamique |
| VPN IPsec (ISAKMP) | Sécurisation backbone |
| NAT/PAT | Accès Internet |
| Apache | Serveur Web |
| MySQL | Base de données |
| NFS | Partage de fichiers |
| Prometheus + Grafana | Monitoring |

##  Services déployés
-  Serveur Web Apache (HTTP/HTTPS)
-  Base de données MySQL avec accès distant sécurisé
-  Partage de fichiers NFS
-  Supervision Prometheus + Grafana

## 🔐 Sécurité
- Tunnels VPN IPsec entre tous les routeurs du backbone
- Chiffrement AES-256 + SHA-256
- Clés pré-partagées ISAKMP

##  Réalisé par
Emna Bahar, Yosr Ben Hamouda, Sarra Ben Boubaker, 
Azer Aissaoui, Jihed Ramedi

**Encadré par :** Mme Safa Cherif & Mr Mohamed Firas Mhalla  
**École :** ESPRIT — 2024/2025
