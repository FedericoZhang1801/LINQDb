# LINQDb

DataBase di Riferimento : https://www.sqlitetutorial.net/wp-content/uploads/2018/03/chinook.zip 

Creare la cartella di destinazione dei file del progetto
Aprire La cartella in VisualStudio
Visualizzare il Terminale di VS
Eseguire nel Terminale di VS la linea di comando " dotnet new console " per creare i file del progetto dotnet
Eseguire la linea di comando " dotnet add package sqlite-net-pcl " per installare il pacchetto di SQLite
Includere la libreria di SQLite usando "using SQLite" nel codice

Creare il collegamento al DataBase di riferimento tramite il metodo SQLiteConnection
es. " SQLiteConnection cn1 = new SQLiteConnection("chinook.db"); "


