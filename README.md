# AnsibleClaude
Ansible pour le cours Linux avancée d'ASR

Le SRV-LAB va contenir le setup et l'inventory.

Pour l'envoi de la configuration vers la machine : 
```ansible-playbook -i inventory.ini setup.yml```

Le setup :
    Configurer des Paquets & Dépendances de base; 
    Configurer le SSH; 
    Configurer Pare-feu; 
    Installer docker; 
    Déploiement de la Plateforme
