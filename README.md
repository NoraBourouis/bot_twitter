# bot_twitter

Consignes de l'exo : 

2. Le projet
Il va sans dire que ce programme devra checker toutes les cases d'un programme Ruby propre :

Utiliser un Gemfile, dans lequel tu pourras trouver les gems dont tu te serviras pour l'exercice : Ruby avec la bonne version, Twitter, Rubocop, Pry, Rspec et Dotenv.
Une architecture de dossier type (lib, spec, etc.).
Un fichier .env dans le .gitignore.
Un README.md qui explique bien les choses

2.1. Il va dire bonjour
Les journalistes sont quasiment les derniers qui croient que Twitter, c'est encore cool : ils sont tous sur la plateforme. Profitons-en ! Fais un bot Twitter qui va contacter les journalistes et promouvoir notre super hashtag. Voici une liste de handles (= noms d'utilisateurs sur Twitter) de journalistes.
Ton objectif est de faire un programme qui en prend 5 au hasard, et qui leur tweet une phrase sympa (une blague, un truc qui leur dit que leur dernier article est cool, un remerciement pour leur rôle central dans le fonctionnement de notre démocratie… ce que tu veux !), avec le hashtag #bonjour_monde. Un seul tweet par journaliste suffit (5 tweet en tout donc) pour éviter d'être trop lourd et de te faire bannir de Twitter.



2.2. Il va liker bonjour
Maintenant que tu as dit bonjour à Internet, nous allons te demander de liker les derniers tweets (minimum les 25 derniers) qui ont le hashtag #bonjour_monde. Cela leur donnera une visibilité de malade en créant une grande chaîne de bienveillance 🌈. Pour cela il existe plein de façons possible… nous te laissons le choix !

2.3. Il va follow bonjour
Maintenant que tu es la star du like, nous allons te demander de follow les dernières personnes (minimum 20) qui ont tweeté avec le hashtag #bonjour_monde. Idem, cela donnera plein de visibilité et vous serez les stars de Twitter 💙.

Comme toute la communauté THP va jouer avec le hashtag #bonjour_monde, n’hésitez pas à vous rencarder entre vous pour faire buzzer un maximum le hashtag. Tous les coups sont permis, donc amusez-vous bien !

2.4 Il like et follow en live
Maintenant tu vas utiliser la fonction Streaming de l'API Twitter afin de réagir en live. Mets en place un robot qui like et follow les comptes tweetant le #bonjour_monde dès l'apparition du Tweet. Pour rendre le programme un peu visuel, n'hésite pas à mettre des puts dès que tu repères un Tweet comme ça (qu'il apparaisse sur ton terminal) ! Et s'ils ne sont pas nombreux, demande à tes potes de Tweeter un peu… mais sans se faire bloquer hein !

Comme il ne réagit qu'en live, ce programme devra tourner en tâche de fond de ton ordinateur.
