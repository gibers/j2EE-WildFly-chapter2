"# j2EE-WildFly-chapter2" 

utilisation simple du hibernate avec fichier de hibernate.cfg.xml.  

L'utilisation se fait avec l'appel des méthodes suivantes : 

Création du schéma en base : 
http://localhost:8080/jboss-hibernate/schemaExport.jsp
Cet appel générera également un fichier nommé hbd2ddl.sql dans le dossier /bin de Wildfly. 

insertion des données en base dans la table catalogue : 
http://localhost:8080/jboss-hibernate/add.jsp

Simple requête pour lister ce qu'il y a en base : 
http://localhost:8080/jboss-hibernate/find.jsp

Mettre à jour la table catalogue : 
http://localhost:8080/jboss-hibernate/update.jsp

Supprimmer quelques lignes de la table : 
http://localhost:8080/jboss-hibernate/delete.jsp

