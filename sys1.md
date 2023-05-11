# **Devoir SYS1**

Dans chaque challenge vous devez télécharger un fichier .pcap; pour ça il faut : <br>
1- Clic droite sur Démarrer le challenge <br>
2- Ouvrir le lien dans un nouvel onglet

## _FTP - AUTHENTIFICATION_

. Ouvrir le fichier ch1.pcap qui se dirige directement vers wireshark <br>
. Clic droit sur FTP <br>
. Suivre, Flux TCP <br>
. Le mot de passe est la chaîne de caractère après le mot "PASS"

## _TELENET - AUTHENTIFICATION_

. Ouvrir le fichier ch2.pcap<br>
. Clic droite sur TCP <br>
. Suivre, Flux TCP <br>
. Le mot de passe est celui qui se trouve après le mot "Password"

## _ETHERNET - TRAME_

. Sur celui la, le site affiche une serie de code hexadecimal. <br>
. Il est donc nécéssaire de le convertir en text, sur votre navigateur tapez **hex to text** <br>
. Une fois la conversion terminer, tapez sur votre navigateur **base64** pour convertir le text obtenu, qui devient le **mot de passe**

## _AUTHENTIFICATION TWITTER_

. Ouvrir le fichier ch3.pcap <br>
. Clic droite sur HTTP <br>
. Suivre, Flux TCP <br>
. Le mot de passe se trouve après le mot "Basic", ne pas prendre "=".

## _BLEUTOOTH FICHIER INCONNU_

. Ouvrir le fichier ch18.pcap <br>
. Appuyez sur HCI EVIT, puis sur "Wireless", et équipements bluetooth <br>
. Copier 0c:b3:19:b9:4f:c6GT-S7390G <br>
. Sur votre navigateur, accedez à SHA1.fr, puis coller 0c:b3:19:b9:4f:c6GT-S7390G, il est important de noté que les caractères en minuscule doit-être transformer en majuscule avant de convertir; après la conversion vous obtenez le mot de passe
