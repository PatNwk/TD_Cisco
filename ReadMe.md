TP Cisco - Configuration de Switches

Bienvenue dans le dépôt TD_Cisco, qui contient les configurations, scripts et documents liés à notre TP sur la configuration des switches Cisco.

📁 Structure du Dépôt

TD_Cisco/
├── 📄 README.md               # Explication du projet et instructions
├── 📂 doc/                    # Fichiers de référence et compte-rendu
│   ├── TD_Cisco_Pratique2.pdf # Le fichier PDF du TP
│   ├── TD_Cisco.md            # Version Markdown du TP
│   ├── schema.png             # Schéma du réseau
│   └── notes.md               # Notes supplémentaires
├── 📂 configurations/         # Fichiers de configuration des switches
│   ├── config_switch.txt      # Config du premier switch
│   ├── reset_switch.txt       # Reset du switch
│   ├── spanning_tree.txt      # Configuration STP
│   ├── firmware_update.txt    # Mise a jour du firmware
│   ├── port_security.txt      # Sécurisation des ports
│   └── dhcp_config.txt        # Configuration DHCP
├── 📂 captures/               # Captures d'écran et logs
│   ├── ping1.png              # Capture d’un ping
│   ├── ping2.png              # Capture d’un ping
│   ├── ping3.png              # Capture d’un ping
│   └── capture_wireshark.png  # Capture Wireshark
└── 

🛠️ Configuration des Switches

1️⃣ Prise en main

Connexion au switch via le port console avec PuTTY.

Réinitialisation du switch aux valeurs d’usine.

Mise à jour du firmware via TFTP.

2️⃣ Sécurisation & SSH

Configuration d’un mot de passe pour le mode privilégié.

Activation de l’accès SSH et désactivation de Telnet.

3️⃣ VLANs et Trunking

Création de 10 VLANs.

Configuration des trunks pour la communication inter-VLAN.

Activation du DHCP sur un VLAN.

4️⃣ Spanning Tree Protocol (STP)

Sélection du Root Bridge.

Configuration du Rapid-PVST pour équilibrer la charge.

5️⃣ Sécurisation des Ports

Activation de PortFast pour les ports utilisateurs.

Activation de BPDU Guard pour prévenir les boucles réseau.

🚀 Automatisation avec les Scripts

setup_vlan.sh : Configure les VLANs automatiquement.

backup_config.sh : Sauvegarde la config du switch.

monitor_traffic.py : Analyse du trafic réseau en temps réel.

📜 Licence

Ce projet est sous licence MIT. Vous êtes libre de le modifier et de le partager.

📨 Contact

Si vous avez des questions ou suggestions, ouvrez une issue sur GitHub ! 🎉

# TD_Cisco
