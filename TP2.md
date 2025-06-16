### 2-1 What are testcontainers?

Testcontainers est une librairie Java qui permet de lancer des containers Docker à la volée pendant les tests. 
C'est utile pour les tests où on veut une vraie bdd au lieu de simplement le mocker.

### 2-2 For what purpose do we need to use secured variables ?

Pour pas qu'elles soient visibles dans le code et on peut également les scopés

### 2-4 For what purpose do we need to push docker images?

On construit l'image une fois et ensuite, on peut exécuter cette meme image sur n'importe quel serveur, environnement ou machine.
Ce qui veut dire qu'on peut dans la CI récupérer cette image pour la déployer ou la tester.