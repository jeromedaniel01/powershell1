Exercice ***Powershell***

Pour creer un fichier avec Powershell la commande est  **New-item** ou l'alias **md**  equivalent Unix ***touch***

Pour copier un fichier avec powershell la commande est  **Copy-Item** ou les alias **copy** **cp** **cpi** equivalent Unix ***cp***

Pour supprimer un fichier avec Powershell la commande est **Remove-item** ou les alias **del** **erase** **rd** **ri** **rm** **rmdir** equivalent Unix ***rm*** 

Pour se deplacer avec Powershell la commande est **Set-Location** ou les alias **cd** **chdir** **sl** equivalent Unix ***cd***

Pour creer un dossier avec Powershell la commande est la meme que pour creer un fichier  **New-Item** equivalent Unix ***mkdir***

La commande pour demander de l'aide avec Powershell est **Get-help** equivalent Unix ***man***

La commande pour afficher l'historique des commmandes precedemment utilisées est **Get-History** ou les alias **clhy** **h** equivalent Unix ***history***

La commande pour afficher les Alias  est **Get-Alias** equivalent Unix ***alias***

La commande pour afficher le contenu  d'un fichier est **Get-Content** ou les alias **cat** **gc** **type** equivalent Unix ***cat***

Differentes **commandes** pour mes recherches

PS C:\Windows\system32> cp C:\Users\jerome\Documents\copie2 -Destination C:\Users\jerome\Documents\copie -recurse
copier un fichier et son contenu grace a l'action -***recurse***


PS C:\Windows\system32> rm  C:\Users\jerome\Documents\copie

**supprimer** un fichier

PS C:\Windows\system32> chdir C:\Users\jerome\Documents\

**se deplacer** a un emplacement defini 

PS C:\Users\jerome\Documents> md 'fichier creation'

**creer** un dossier "fichier creation " ou l'on se trouve

PS C:\Users\jerome\Documents\fichier creation> New-Item -Path . -Name "creation.txt" -ItemType "file"

**creer** un fichier "creation.txt"

PS C:\Users\jerome\Documents> get-help rm

commande d'**aide** pour certaines actions  ici  aide pour l'action supprimer

PS C:\Users> Get-History

Pour afficher l'**historique des commandes** mais juste ceux de la session en cours contrairement a Unix qui affiche toutes les commandes passées

PS C:\Users\jerome> cat .\Documents\copie2\exercice-powershell.txt

commande pour afficher le **contenu** d'un fichier 

PS C:\Users\jerome> alias

En ce qui concerne les **alias**  la commande est la meme que sur Unix