Section 1 : Configuration du compilateur 

Pour compiler le fichier Par exemple "App01.cs":
 Methode 1 :  
1.Ajouter la variable d' environement pour que le compilateur fonctionne : 
 Windwos 10 : 
 Control Panel -> System and Security -> System -Advanced System -> Edit Variable environement
 Ajouter le path dans le system variable : C:\Program Files (x86)\MSBuild\14.0\Bin
1.Ouvrir La ligne de commande cmd as Adiminstateur
2. ->Tu  rentre aux  fichier de l' application  : cd PathApplication
   ->Tu tape  : csc fichier.csc  


Section 2 : Utilities pour manipuler le programme : 

1./out: Donner le nom qu'on veut au fichier lors de la compilation : csc /out:nomChisie.exe fichier.cs
2./target : Lors de la compilation tu peux choisir entre trois choix (.exe,winexe,library) :csc /target

