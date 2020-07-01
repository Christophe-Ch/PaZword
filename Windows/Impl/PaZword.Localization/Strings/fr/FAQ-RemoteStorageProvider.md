### Question fr�quemment pos�es

#### Est-il obligatoire de choisir un service de stockage dans le cloud?

Pas du tout, mais c'est fortement recommand�.

#### Qu'est-ce qu'un service de stockage dans le cloud apporte?

Cel� permet � PaZword de faire une sauvegarde de votre coffre-fort dans le cloud. C'est utile pour r�cup�rer vos donn�es apr�s avoir formatt� votre machine, ou lorsque vous utilisez PaZword sur une autre machine.

#### Pourquoi utiliser mon service de stockage dans le cloud personnel au lieu d'un server pour PaZword?

PaZword est un logiciel Open Source fait par un d�veloppeur dans son temps libre. Les servers ont un co�t, et le d�veloppeur ne souhaite payer le prix du traffic et g�rer la s�curit� de son propre server. Le d�veloppeur pense �galement que les utilisateurs suspecterons la mani�re dont leur coffre-fort est g�r�. De ce fait, utiliser un service de stockage dans le cloud existant offre un bon compromis entre le co�t et la s�curit�.

#### Est-ce s�curis�?

PaZword chiffre toutes vos donn�es via votre cl� de r�cup�ration sur votre machine et dans le cloud. Les donn�es ne peuvent �tre lu sans la cl� de r�cup�ration.

#### O� est stock� ma cl� de r�cup�ration?

Votre cl� de r�cup�ration est stock� dans le [Windows Credential Manager](https://support.microsoft.com/en-us/help/4026814/windows-accessing-credential-manager) tant que vos param�tres le permettent (vous pouvez lez changer plus tard).
M�me si PaZword conserve la cl� de r�cup�rer dans le Windows Credential Manager, il est important que vous conservew une copie de votre cl� au cas ou elle soit supprim�e. La cl� de r�cup�ration ne sera pas stock� dans le service de stockage personnel dans le cloud et le d�veloppeur de PaZword ne la garde pas non plus.

#### Comment supprimer mon coffre-fort de mon service de stockage personnel dans le cloud?

Vous pouvez supprimer vos donn�es dans le cloud � tout moment en d�sactivant la synchronisation dans les param�tres de PaZword, puis en supprimant les fichier depuis le dossier d'application de votre service de stockage personnel dans le cloud.
Par exemple, sur Microsoft OneDrive et Dropbox, vous trouverez votre les donn�es de votre coffre-fort dans le dossier _/Applications/PaZword_.

#### J'ai d'autres questions

Vous pouvez trouver des r�ponses sur votre moteur de recherche favoris sur internet, ou bien en contactant le d�veloppeur [ici](https://www.velersoftware.com/contact.php).