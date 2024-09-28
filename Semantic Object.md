[[Semantic Object#Créer un Semantic Object|Créer un semantic object]]

### **Qu'est-ce qu'un Semantic Object dans SAP Fiori ?**

Un "semantic object" est un concept essentiel dans SAP Fiori qui permet de définir le contexte métier d'une application ou d'une action utilisateur au sein de l'expérience Fiori. Il représente un objet métier logique, tel qu'un client, une commande, un produit ou un employé, et permet d'établir des liens entre ces objets et les différentes applications SAP qui les gèrent.

### **Principaux aspects des Semantic Objects :**

1. **Définition** : Un semantic object encapsule un concept métier spécifique comme un client, une commande de vente, ou un produit. Il s'agit d'une abstraction d'un objet métier qui est associée à un ensemble d'actions (par exemple, afficher, créer, modifier) pouvant être effectuées sur cet objet.

2. **Navigation** : Les semantic objects jouent un rôle clé dans la navigation au sein des applications Fiori. Ils permettent de créer des liens directs vers des applications spécifiques, offrant ainsi une navigation fluide et efficace. Par exemple, si vous avez un semantic object "SalesOrder," vous pouvez directement accéder à une application affichant une commande de vente particulière en utilisant une URL qui inclut ce semantic object et ses paramètres.

3. **Intégration et cohérence** : Les semantic objects sont utilisés en combinaison avec des actions sémantiques qui définissent les opérations possibles sur un objet (par exemple, "display," "edit," "create"). Cette intégration garantit une expérience utilisateur cohérente à travers les différentes applications Fiori, en assurant que les mêmes objets métiers sont accessibles de manière uniforme, quelle que soit l'application utilisée.

4. **Flexibilité et personnalisation** : Les développeurs peuvent créer des semantic objects personnalisés pour répondre à des besoins métiers spécifiques. Cela permet d’étendre et de personnaliser les applications Fiori, offrant ainsi une solution adaptée à chaque entreprise.

5. **Utilisation dans le SAP Fiori Launchpad** : Dans le Launchpad Fiori, les tuiles sont souvent définies sur la base des semantic objects, permettant aux utilisateurs d'accéder rapidement aux applications pertinentes et d'effectuer des actions liées à ces objets métiers. Cela crée une expérience utilisateur intuitive et centrée sur les tâches.

### **Exemple d'utilisation :**

Supposons que vous ayez un semantic object appelé "SalesOrder". Les actions associées à cet objet pourraient inclure :
- **Display** : Afficher les détails d'une commande de vente.
- **Create** : Initier la création d'une nouvelle commande de vente.
- **Approve** : Approuver une commande de vente en attente.

Lorsqu'un utilisateur clique sur une tuile liée à "SalesOrder" dans le Launchpad Fiori, le semantic object et l'action associée guident le système vers l'application appropriée.

### **Conclusion**

Les semantic objects dans SAP Fiori jouent un rôle fondamental dans la définition de la structure, la navigation et l'intégration des applications, améliorant ainsi l'expérience utilisateur en fournissant un contexte métier cohérent et en facilitant l'accès aux fonctionnalités associées. Grâce à ce concept, SAP Fiori permet une navigation fluide et intuitive entre les différents objets métiers, offrant une expérience centrée sur les tâches et les besoins des utilisateurs.


# Créer un Semantic Object

