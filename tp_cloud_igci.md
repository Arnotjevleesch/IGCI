# TP CLOUD IGCI

1. Sur un compte github public personnel, forker https://github.com/spring-projects/spring-petclinic

2. Sur travis-ci.com, faire le lien avec ce nouveau repository

3. Faire un premier push, cela doit déclencher un build sur travis et l'envoi d'un mail
   
4. Un peu de lecture
  - https://docs.travis-ci.com/user/for-beginners/
  - https://docs.travis-ci.com/user/job-lifecycle/
  - les logs du build

5. Les variables d'environnement
  - https://docs.travis-ci.com/user/environment-variables
  - Afficher quelques variables utiles (TRAVIS_*) avant l'install

6. Mettre en place une analyse statique du code
  - https://docs.travis-ci.com/user/sonarcloud/

7. Afficher les badges du build et de l'analyse dans github

8. Créer une image docker
  - https://docs.travis-ci.com/user/docker/

9. Déploiement par container sur Heroku
  - https://devcenter.heroku.com/articles/heroku-cli
  - https://devcenter.heroku.com/articles/container-registry-and-runtime

10. Builder avec 2 jdk (oraclejdk8 et openjdk11) mais déployer une seule fois
  - https://docs.travis-ci.com/user/build-matrix/
  - https://blog.travis-ci.com/2017-09-12-build-stages-order-and-conditions
  - https://docs.travis-ci.com/user/conditions-v1
