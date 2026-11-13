<<<<<<< HEAD
# DoctorWhen 🩺

Application Java de gestion de rendez-vous médicaux.

## 📋 Présentation
=======
# DoctorWhen 

Application Java de gestion de rendez-vous médicaux.

##Présentation
>>>>>>> ae9d7d5802bdb93d9652ddce3f0f2086b91f4b35

**DoctorWhen** est une application en ligne de commande développée en Java. Elle permet de gérer les rendez-vous d'un cabinet médical à travers un menu interactif.

Le projet a été réalisé dans le cadre de mon apprentissage de la programmation Java et de la programmation orientée objet.

<<<<<<< HEAD
## ✨ Fonctionnalités
=======
##Fonctionnalités
>>>>>>> ae9d7d5802bdb93d9652ddce3f0f2086b91f4b35

- **Authentification** : accès à l'application avec un identifiant et un mot de passe.
- **Prise de rendez-vous** : création d'un rendez-vous avec les informations du patient.
- **Vérification des disponibilités** : contrôle des créneaux déjà réservés et exclusion des dates passées.
- **Gestion des horaires** : rendez-vous du lundi au vendredi, sur les plages horaires autorisées.
- **Gestion des jours fériés** : prise en compte des jours fériés en Alsace (liste définie dans le code).
- **Calcul des tarifs** : association d'un tarif à chaque type de consultation et calcul de la prise en charge selon l'âge du patient.
- **Référence client** : génération automatique d'une référence à partir des initiales, de la date du rendez-vous et du motif.
- **Annulation** : suppression d'un rendez-vous.
- **Modification** : déplacement d'un rendez-vous.
- **Recherche** : recherche d'un rendez-vous à partir des premiers caractères de sa référence client.

<<<<<<< HEAD
## 🛠️ Technologies utilisées
=======
##Technologies utilisées
>>>>>>> ae9d7d5802bdb93d9652ddce3f0f2086b91f4b35

- Java
- Java Collections Framework (`ArrayList`, `HashMap`, `Set`)
- Java Time API (`LocalDateTime`, `LocalDate`, `DateTimeFormatter`)
- Programmation orientée objet (POO)

<<<<<<< HEAD
## 📁 Structure du projet
=======
##Structure du projet
>>>>>>> ae9d7d5802bdb93d9652ddce3f0f2086b91f4b35

```text
DoctorWhen/
│
├── AppointmentDetails.java
├── AppointmentForm.java
├── CancelAppointment.java
├── ChangeAppointment.java
├── ContinueLoop.java
├── CreateClientReference.java
├── FilterAppointments.java
├── Login.java
├── MAINMENU.java
├── PriceCodes.java
│
└── README.md
```

<<<<<<< HEAD
## ⚙️ Installation et lancement
=======
##Installation et lancement
>>>>>>> ae9d7d5802bdb93d9652ddce3f0f2086b91f4b35

### Prérequis

- Java Development Kit (JDK 9 ou supérieur).
- Un terminal (ou Visual Studio Code).

Vérifier l'installation de Java :

```bash
java -version
javac -version
```

### Compilation

Depuis la racine du projet :

```bash
javac -d out DoctorWhen/*.java
```

### Exécution

```bash
java -cp out DoctorWhen.MAINMENU
```

<<<<<<< HEAD
## 🔐 Authentification
=======
##Authentification
>>>>>>> ae9d7d5802bdb93d9652ddce3f0f2086b91f4b35

L'application utilise actuellement des identifiants définis directement dans `MAINMENU.java`.

Il s'agit d'une authentification de démonstration, qui devra être remplacée par un système sécurisé pour une utilisation réelle.

<<<<<<< HEAD
## ⚠️ Limitations actuelles
=======
##Limitations actuelles
>>>>>>> ae9d7d5802bdb93d9652ddce3f0f2086b91f4b35

- Les données sont conservées uniquement en mémoire pendant l'exécution de l'application.
- Les rendez-vous ne sont pas sauvegardés dans une base de données.
- L'authentification est simplifiée.
- La gestion des jours fériés repose actuellement sur une liste de dates définies dans le code.

<<<<<<< HEAD
## 🚀 Perspectives d'amélioration
=======
##Perspectives d'amélioration
>>>>>>> ae9d7d5802bdb93d9652ddce3f0f2086b91f4b35

- Intégration d'une base de données.
- Sécurisation de l'authentification.
- Persistance des informations patients et rendez-vous.
- Amélioration de la gestion des modifications et annulations.
- Développement d'une interface graphique.
