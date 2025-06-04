# 🐕 MbuaOS – Le Network Operating System souverain de la RDC

**MbuaOS** est un système d'exploitation réseau léger, modulaire et souverain, conçu pour les infrastructures critiques, les fournisseurs d'accès congolais, les administrations, et les environnements isolés. Basé sur Buildroot et le noyau Linux, il vise à offrir un contrôle total sur les fonctions de routage, pare-feu, VPN, ZTNA, et SD-WAN.

---

## 🚀 Caractéristiques techniques

- 📦 Buildroot minimal (musl/glibc) + noyau Linux 6.x
- 🔐 `nftables` pour pare-feu d'état + règles dynamiques
- 🌐 IP statique et routage configurable
- 🔒 Accès SSH via Dropbear dès le boot
- ⚙️ Overlay Linux propre pour configuration embarquée
- 🛠️ Préparation d’une WebUI (MbuaWeb) & API (FastAPI)
- 🔗 Intégration future avec FRR, WireGuard, StrongSwan, NetBird

---

## 🧱 Structure de démarrage

```bash
make mbuaos_defconfig
make
