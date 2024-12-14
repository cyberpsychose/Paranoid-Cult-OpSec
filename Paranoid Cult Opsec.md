L'**OpSec** (Operational Security) est la pratique de protéger des informations sensibles en identifiant des éléments critiques, en analysant des menaces et vulnérabilités, et en mettant en place des mesures pour empêcher la divulgation non autorisée.

```
CLAUSE DE NON-RESPONSABILITÉ : LE GROUPE PARANOID N'EST PAS RESPONSABLE DE
L'USAGE QUE VOUS FAITES DE CETTE OPSEC. IL S'AGIT D'UN GUIDE
SUR LA PROTECTION DE LA VIE PRIVEE ET LA SECURITE. NE FAITES
PAS DE CHOSES ILLÉGALES ET NE NOUS BLÂMEZ PAS ENSUITE. 
```

Dans notre OpSec, nous allons aborder plusieurs thèmes :

1. Les forces de l'ordre
2. Les mots de passe
3. Authentification à multi-facteur
4. Stockage sécurisé et chiffré
5. Stockage sécurisé et suppression de l'espace libre
6. OS mobile sécurisé, stockage et effacement de l'espace libre
7. Sécurité des réseaux sociaux / des communications
8. VPN, TOR ou I2P
9. Disparaître d'internet
10. Autres conseils
11. disparaitre d'internet et du monde

## les forces de l'ordre 
### droit de garder le silence

> [!quote] Suicide social - Orelsan
>*ces saletés de flics*
>*Qui savent pas construire une phrase en dehors de leur sales répliques*

Vous vous souvenez de cette phrase que tous les policiers disent dans les films ? **"Vous avez le droit de garder le silence. Tout ce que vous direz pourra être retenu contre vous devant un tribunal."** C'est le meilleur conseil qu'ils puissent vous donner, mais trop peu de gens l'utilisent. La plupart des pays occidentaux vous offrent ce fameux droit de garder le silence, ce droit est de base utilisé contre l'auto-incrimination. _**UTILISEZ CE DROIT**_. Malheureusement, 98 % des personnes interrogées aux États-Unis n'invoquent pas leur droit de garder le silence. Ils pensent que ne pas parler les rendra plus suspects, ou que les forces de l'ordre seront plus gentilles avec eux s'ils parlent.

Le fait est que les forces de l'ordre _**ne sont pas vos amis**_. Elles vont juste monter un dossier sur vous et tout ce que vous leur dites sera utilisé contre vous. Aux États-Unis, les forces de l'ordre ont légalement le droit de vous **mentir** et en France, elles ont légalement le droit de vous **manipuler** tant qu'elles ne vous mentent pas sur vos droits. Si elles vous promettent une **"bonne offre"** ou jurent de se **"battre"** pour vous contre le procureur, c'est _**un putain de mensonge**_. Tant que vous n'avez pas d'avocat et qu'elles ne vous sortent pas un papier à signer prouvant la fiabilité de leur promesse, ne croyez pas en leurs paroles.

### comment invoquer votre droit de garder le silence?
Il ne va pas vous suffire de juste dire, *"je devrais avoir mon avocat"*, *"je ne veux pas parler"* ou *"je vais garder le silence"*. Le système juridique est tellement fucked up que vous devez dire une phrase bien plus spécifique du style ***"J'invoque mon droit de garder le silence."***
N'importe quel bon avocat vous demandera de **fermer votre gueule** si vous souhaitez invoquer ce droit. Ils ***VONT*** essayer de vous faire parler même après avoir dit cette phrase, mais continuez de vous taire.

### les seules questions que vous devez poser
1. Pourquoi suis-je ici ?
2. Suis-je détenu ou en état d'arrestation ?
3. (S'ils répondent non aux deux précédentes questions) Suis-je libre de partir ?
4. (Si oui à la question précédente) ****PARTEZ SANS RÉFLÉCHIR PLUS QUE ÇA****

Vos données ne sont bien sûr pas à l'abri des forces de l'ordre, mais un **"accident" qui détruit votre matériel** peut vite arriver dans une vie, ou avoir **"oublié" votre mot de passe car trop complexe** et rester silencieux après ça ;)


Souvenez-vous, ***moins vous parlez, moins votre dossier sera rempli, moins il y aura de choses qu'ils pourront exploiter ou aller vérifier, et donc plus de chances que cela finisse en affaire sans suite.***


## les mots de passes

***Vos mots de passe doivent contenir :***
1. Au moins 12 caractères
2. Un mélange de lettres majuscules / minuscules
3. Un mélange de lettres et de chiffres
4. Au moins un caractère spécial (#, ?, @)

***Les mots de passe faibles sont des mots de passe du genre :***
1. Les mots que l'on peut retrouver dans un dictionnaire
2. Qu'on peut retrouver dans des wordlists de mots de passe
3. Des mots de passe du style "azerty", "12345", "salut15100", etc.
4. Des infos personnelles telles que votre numéro de sécurité sociale, votre anniversaire, etc.


### informations tres sensible
Si vous stockez des informations vraiment très sensibles sur lesquelles personne ne doit tomber, vous devez créer des mots de passe bien plus longs, par exemple une trentaine de caractères. Vous pouvez juste mémoriser plusieurs mots de passe et tous les réunir en un seul.

Je vous recommande personnellement d'utiliser **KeePassXC**, c'est un gestionnaire de mots de passe open source. Le mot de passe de votre KeePassXC doit bien sûr faire au minimum 30 caractères. Vous pouvez même générer des mots de passe aléatoires et sécurisés sur KeePassXC.


## Auth multi-facteur
Les facteurs d'authentification sont les suivants :
1. Quelque chose que vous savez : un mot de passe que vous connaissez / vous vous souvenez.
2. Quelque chose que vous avez : dispositif de sécurité matériel / jeton.
3. Quelque chose que vous êtes : biométrie (NON recommandée en général, à moins qu'elle ne devienne une option APRÈS l'utilisation d'un facteur ci-dessus).

Si vous utilisez une base de données pour stocker vos mots de passe (ou pas), je vous recommande l'utilisation d'une YubiKey ou OnlyKey. Vous pouvez configurer ces dispositifs en mode mot de passe à usage unique (One Time Password). Combinez cela avec quelque chose que vous connaissez et c'est bon, vous avez la 2FA (authentification à deux facteurs).


![[Pasted image 20241214180256.png]]
![[Pasted image 20241214180342.png]]

## stockage sécurisé et encrypté
**VOTRE SÉCURITÉ EST JUSTE LE REFLET DU CRYPTAGE DE VOTRE OS !**

Si vous ne pensez pas à encrypter votre OS ou si vous laissez votre PC allumé sans l'éteindre en partant, même si le disque est encrypté, vous commettez une erreur. Les keufs ou des personnes randoms pourraient pendant votre absence en profiter pour y installer un virus, des keyloggers, des logiciels d'accès à distance, ou des éléments incriminants pour vous piéger. Je vous conseille personnellement d'utiliser Linux LUKS, qui est une méthode de chiffrement de disque complet.

**VeraCrypt**
VeraCrypt vous permet de créer des volumes encryptés ou, si vous êtes sur Windows, de crypter l'OS tout entier.
[https://www.veracrypt.fr/en/Downloads.html](https://www.veracrypt.fr/en/Downloads.html)

Si vous avez des données très sensibles, utilisez juste un conteneur de stockage encrypté. Vous pouvez définir et changer le mot de passe originel (2FA recommandé) et aussi choisir les algorithmes de chiffrement et de hachage.

En algorithmes de cryptage, il y a : AES, Camellia, Kuznyechik, Serpent, Twofish, Cascades.

Algorithmes de hachage (recommandés) : SHA-512, Whirlpool.

Jusqu'à ce qu'ils soient décryptés, les volumes VeraCrypt n'ont pas de signature, on ne peut donc pas savoir que votre conteneur est un conteneur VeraCrypt.

## stockage sécurisé et suppression de l'espace libre

À ce stade, vous devriez utiliser un système de fichiers encrypté ou un conteneur, comme décrit ci-dessus pour les tours et laptops.

***Juste supprimer ne suffira pas :*** 
Si vous mettez un fichier non encrypté dans votre disque dur sans être crypté, et que vous le supprimez simplement, il n'a pas vraiment été supprimé. **Les données sont encore entièrement récupérables** à 100% et seront exploitées.

Si vous êtes sur le point de supprimer un fichier sensible, ou de le déplacer vers un appareil encrypté ou un volume encrypté mais qu'à un moment il a touché votre disque non crypté, vous devrez utiliser un effaceur d'espace libre ou un outil d'effacement sécurisé.

Parmi les outils connus sur Windows pour effectuer cette tâche, il existe [Eraser](https://eraser.heidi.ie/).
En écrasant tout l'espace libre de ce disque dur, vous rendez la récupération des informations supprimées bien plus difficile.

## OS mobile sécurise, stockage et effacement de l'espase libre

Si vous utilisez un iPhone, déjà **passez sous Android**, mais si vous ne pouvez pas : ne **stockez jamais de données sensibles dessus**. Si les forces de l'ordre sont assez motivées, elles finiront par y accéder, et personnellement, ce n'est pas un appareil sécurisé.

Avec un Android, vous pouvez faire BEAUCOUP plus :
1. Si vous pouvez **rooter l'appareil** : 
La norme actuelle, à mon avis, est d'obtenir un **Google Pixel 6**, de rooter le téléphone, et d'installer dessus **GrapheneOS**, qui permet de sandboxer les apps et les permissions, et utilise une allocation de mémoire sécurisée arrêtant toutes les attaques courantes. Un autre bon OS pour protéger votre vie privée est **CalyxOS**.

Si vous n'avez pas de Google Pixel, je vous recommande d'installer LineageOS. Ce système d'exploitation n'est pas totalement configuré pour la sécurité, mais vous pouvez suivre quelques guides en ligne qui vous permettront de le sécuriser à un niveau élevé.


https://www.reddit.com/r/LineageOS/comments/gaxek2/how_to_increase_the_security_and_privacy_of/

https://medium.com/@securitystreak/securing-an-android-phone-or-tablet-c8c6166b2586

Si vous ne pouvez pas rooter l'appareil, les conseils suivants seront toujours aussi utiles, mais vous serez plus vulnérable à l'espionnage si votre téléphone se prend une backdoor ou est compromis.

2. Utilisez une couche de chiffrement supplémentaire :
DroidFS est un outil qui vous permet de créer des volumes encryptés sur Android, avec son propre explorateur de fichiers intégré. Vous pouvez utiliser les algorithmes de chiffrement AES-GCM ou XChaCha20, ce qui le rend très rapide sans sacrifier énormément de sécurité. Cela ne vous protégera pas contre les enregistrements d'écran, les keyloggers, les rootages compromis ou les dumps de mémoire. Restez à l'écart de tout appareil pouvant être dangereux.

3. Utilisez Extripater pour écraser l'espace libre :
Si quelque chose de sensible touche quelque chose en dehors de DroidFS, utilisez une application comme Extripater pour effacer l'espace libre.

4. Sécuriser les réseaux sociaux et les communications :
Si vous partagez des informations sensibles sur les réseaux sociaux comme Twitter, Instagram, etc., ARRÊTEZ. Toutes ces informations peuvent facilement être citées par les forces de l'ordre. Ces plateformes ont des politiques de rétention des données qui conservent tout ce qui est posté.

**voici un article montrant ce que nos bon vieux amis du FBI peuvent obtenir depuis plusieur  application encrypté**  (Imessage, Line, Signal, Telegram ect)
https://therecord.media/fbi-document-shows-what-data-can-be-obtained-from-encrypted-messaging-apps


| reseau sociaux | information obtenable par le FBI                                                                                                                                                                                                                   |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| qTox           | totallement encrypté et user friendly de base                                                                                                                                                                                                      |
| Signal         | No message content, date et heure d'enregistrement d'un utilisateur, date de la derniere connexion d'un utilisateur au service                                                                                                                     |
| Telegram       | no message content, Aucune information de contact, en cas d'enquete terroriste telegram peut divulguer l'adresse IP et le numéro de téléphone aux autorité compétentes                                                                             |
| Threema        | no message content, le numero de tel et l'adresse mail donnée par l'utilisateur, push token si le systeme de push est utiliser, cléé publique, data (sans heure) de creation de l'identifiant Threema + date (Sans heure) de la derniere connexion |
| Matrix         | No message content (chiffré de bout en bout par défaut), risque lié au metadonnees                                                                                                                                                                 |

***NOTES POUR TELEGRAM***
l'article date de 2021, et comme vous le savez Pavel Durov, PDG de Telegram a ete arreter et a collabore avec les forces de l'ordre, maintennant, le fbi peut avoir acces aux  adresses IP et des numéros de téléphone des utilisateurs soupçonnés d'activités criminelles, pu juste le terrorisme.


> [!important] Note pour telegram
> l'article date de 2021, et comme vous le savez **Pavel Durov**, PDG de Telegram a ete arreter et a **collabore avec les forces de l'ordre**, maintennant, le fbi peut avoir acces aux  **adresses IP** et des **numéros de téléphone** des utilisateurs **soupçonnés d'activités criminelles**, pu juste le terrorisme



## VPN, TOR ou I2P
Personnellement, j'utilise **toujours** un VPN pour cacher mon IP. J'utilisais aussi [cock.li](https://cock.li) pour mes mails et des mails russes. Si vous n'avez pas de VPN, vous pouvez profiter de **wifi public gratuit pour masquer votre vraie IP**.


Si vous utilisez une **carte** pour **acheter un VPN**, ces **informations sont stockées**, et grâce à elles, le **gouvernement peut plus facilement vous surveiller**.


Si vous voulez acheter un VPN, utilisez de la **crypto**, plus précisément **Monero**.

Voici quelques VPN fiables qui acceptent Monero comme moyen de paiement :
1. **iVPN**
2. **Cryptostorm**
3. **Mullvad**

TOR et I2P sont fondamentalement différents d'un VPN. Un VPN est en quelque sorte une entité centralisée, et vos données sont tunnelées par l'intermédiaire de cette entité. TOR et I2P sont des réseaux décentralisés gérés par des bénévoles qui vous assurent l'anonymat et l'accès à des services tels que le "dark web".

**TOR** :
TOR est plus mature et plus grand, il se concentre sur l'accès anonyme au réseau et sur les services cachés secondaire.

**I2P** :
Sécurité beaucoup plus élevée et moins exploitable, ils se concentrent sur les services cachés en premier et sur le clearnet en second lieu.


## Autres conseils
En fonction de votre situation, vous devez connaître certaines possibilités.

**Si vous vous êtes fait totalement doxer**, envisagez d'aller dans un état vous permettant d'obtenir un changement de nom, ou changez votre nom 6 mois après, quand les gens auront oublié. Avec ce nouveau nom doivent venir de nouveaux comptes, nouveau numéro, etc.

**Ne dites rien de compromettant ou juste stupide**.
Si vous vous faites accuser d'être un pédophile ou quoi que ce soit d'autre, n'avouez jamais quoi que ce soit que vous avez fait, ou même que vous n'avez pas fait. C'est l'équivalent de se tirer une balle dans le pied. Pour les forces de l'ordre, chaque chose avouée est une pépite d'or pour eux.

**Laissez les idiots être idiots**.
Si des gens stupides font de faux screens ou de fausses preuves qu'ils vont donner à la police, voyez ça comme une bonne chose. Plus ils donnent de choses fausses à la police, plus les forces de l'ordre ne prendront pas l'enquête au sérieux et ça finira en affaire sans suite. Et s'il y a vraiment trop de fausses preuves envoyées, ils auront juste la flemme d'en faire un dossier et de tout lier entre eux.

**Les screens ne veulent pas forcément dire que vous êtes coupable**.
Pour que des screens aient un impact sur votre affaire, il faut que les forces de l'ordre demandent au réseau social sur lequel a été pris le screen si ces informations existent. Si elles ont été supprimées et si elles n'existent juste pas, les screens ont donc souvent aucun impact. Même les archives peuvent finir par être trafiquées, mais c'est déjà mieux que des captures d'écran. Heureusement que la plupart des humains sont trop cons pour le comprendre.

**Disparaître un certain temps**.
Au bout d'un certain temps, les gens finissent par se lasser. Au bout de 6 mois, vous pouvez être sûr qu'ils ont oublié.

## derniere etape, disparaite d'internet totalement
Vous allez commencer par appeler toutes les entreprises ayant des informations sur vous, telles que prénom et nom, et leur demander de changer votre prénom et nom par quelque chose de pas trop évident. Par exemple, si vous vous appelez **Thomas Carra**, faites prétendre une faute lors de l'inscription et demandez à remplacer par un truc du style **Toma Caro**.

Une semaine plus tard, demandez à changer d'autres informations telles que l'email qu'ils ont de vous, etc.

Encore une semaine plus tard, demandez-leur de supprimer vos informations. S'ils refusent ou disent le faire sans jamais le faire, au moins ils auront maintenant des informations falsifiées sur vous.

Faites vos transactions uniquement en Monero ou en cash, ou en carte prépayée.

Achetez un dumb phone et un vieux PC, que vous utilisez uniquement sous VPN ou dans un wifi public.

Utilisez un prête-nom (quelqu'un qui signera vos factures, etc. à votre place, ce sera maintenant impossible de vous faire avoir à cause d'un fichier client).

### Pseudocide
Il y a trois moyens de disparaître de ce monde. Pour le premier, vous allez devoir :
1. Partir aux USA
2. Être associé à la mafia
3. Vous faire chopper
4. Témoigner contre la mafia
5. Avoir la chance d'avoir accès au **Witness Security Program**, qui vous permettra de créer une nouvelle identité légalement. Selon les États-Unis, aucun être humain ayant eu accès à cette fonctionnalité n'a jamais été retrouvé.

Pour le deuxième, vous allez devoir :
1. Aller dans un pays bien corrompu sans extradition (Pérou, Argentine, Chili, etc.)
2. Aller dans une morgue
3. Vous faire passer pour votre frère et dire que ce cadavre est vous
4. L'enterrer
5. Payer les autorités pour en faire un rapport
6. Envoyer le rapport à votre ambassade
Et c'est bon, vous êtes actuellement vu comme mort.

La troisième est appelée **"la mort en kit"**, vous allez devoir :
1. Aller aux Philippines
2. Payer une mafia pour qu'elle fasse cette fameuse mort en kit
La mort en kit contient tout : un faux rapport de police, avec de faux témoins, un corps incinéré, enfin la totale.

# Conclusion


> [!quote] J.J Luna dans "How To Be Invisible"
> "You may feel this is necessary if there's a bounty on
your head or a contract on your life, but at this point, is life still
worth living?"


- En cherchant constamment des moyens de rester anonyme, on finit par abandonner sa vie normale et sombrer dans la paranoïa.

- S'impliquer dans des affaires de mafia pour obtenir une nouvelle identité, c'est sacrifier sa tranquillité d'esprit pour une sécurité illusoire.

- Simuler sa propre mort pour disparaître, c'est renoncer à tout ce qui fait de nous une personne, pour vivre dans la peur constante d'être découvert.

- À force de chercher des méthodes toujours plus extrêmes pour rester anonyme, on finit par perdre le contact avec la réalité et les relations humaines.

- L'obsession de l'OpSec peut transformer une vie en une série de manœuvres désespérées, où chaque décision est dictée par la peur et la paranoïa. Vous finirez soit par vous pendre, soit dans la peur constante de vous faire rattraper par un passé détruit, vous serez parano.


*Paranoid Cult*