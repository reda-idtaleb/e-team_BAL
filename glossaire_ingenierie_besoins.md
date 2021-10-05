# Glossaire ingénierie des modèles

### Utilisateur (User)
Un utilisateur est une personne disposant d'un compte utilisateur. Il peut avoir accès à des fonctionnalités plus ou moins élargies en fonction de son rôle.  

### Administrateur (Administrator)
Un administrateur dispose de fonctions de paramétrages de l'application. Il est également averti par un gestionnaire de notifications (NotificationManager) lorsqu'il est nécessaire de commander des articles auprès de fournisseurs.    

### Etudiant (Student)
Un étudiant dispose uniquement de fonctionnalités liées à l'achat d'articles.

### Gestionnaire de données (DataManager)
Le gestionnaire de données permet d'actualiser les données liées aux articles, adhérents et commandes.

### Commande (Order)
Une commande représente un achat d'articles ou de livres de la part d'un étudiant. Il peut s'agir d'une commande de livres (BookOrder) ou de fournitures (SchoolSuppliesOrder).

### Paiement (PaymentStrategy)
Un paiement est nécessaire pour valider une commande. Il peut être de type chèque, carte bancaire ou virement bancaire.

### Gestionnaire de notifications (NotificationManager)
Le gestionnaire de notifications informe l'administrateur d'évènements importants en fonction des paramètres de l'application.

### Article (Product)
Il représente un article physique qui peut être un livre ou un article de fournitures scolaires.