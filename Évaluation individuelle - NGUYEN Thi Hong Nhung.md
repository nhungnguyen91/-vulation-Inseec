# Évaluation individuelle

## Programmation - Coaching

```
Nom : NGUYEN
Prénom : Thi Hong Nhung
URL de votre compte Github : https://github.com/nhungnguyen91
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
L'interaction client-serveur est la base principale des applications web. Il désigne un mode de communication à travers le réseau entre plusieurs programmes.
```



 ### 2. HTML est un langage côté... 

```
HTML est un langage informatique utilisé sur Internet. On utilise ce langage pour créer des pages web.
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>
    
	<head>
  	</head>
 
    <body>
    </body>
 
</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en rose en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
div p.rose {
    color: pink;
}
```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap a été créé en 2011 chez Twitter. Bootstrap est un groupe d'outils pratiques et nécessaires pour la création du design d'applications web et de sites comme animation, graphisme et interactions. Il est également gratuite avec open source. Il contient les codes CSS et HTML, des boutons, des formulaires, etc.
```







### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
  </body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div class="container">
  <div class="row">
    <div class="col-4">
        Google
    </div>

    <div class="col-4">
        Microsoft
    </div>

    <div class="col-4">
        Apple
    </div>
</div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class="container">
  <div class="row">
    <div class="col-4">
        <img src="https://www.1ere-position.fr/wp-content/uploads/2018/02/google-logo-2013-1.png" />
    </div>

    <div class="col-4">
        <img src="https://www.one-system.fr/wp-content/uploads/2016/05/logo-microsoft.png" />
    </div>

    <div class="col-4">
        <img src="https://www.makrea.com/1226-thickbox_default/sticker-logo-apple.jpg" />
    </div>
</div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div class="container">
  <div class="row">
    <div class="col-4">
      <a href="https://google.com">
        <img src="https://www.1ere-position.fr/wp-content/uploads/2018/02/google-logo-2013-1.png" />
      </a>
    </div>

    <div class="col-4">
      <a href="https://microsoft.com">
        <img src="https://www.one-system.fr/wp-content/uploads/2016/05/logo-microsoft.png" />
      </a>
    </div>

    <div class="col-4">
      <a href="https://apple.com">
        <img src="https://www.makrea.com/1226-thickbox_default/sticker-logo-apple.jpg" />
      </a>
    </div>
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
Ruby est un langage de programmation libre. Il est aussi un langage open-source dynamique qui met l'accent sur la productivité et la simplicité.
```



### 11. Listez-moi tous les types de données que vous connaissez.

```
- Types alphanumériquesL (Les chaînes de caractères)
- Types numériques (Les virgule flottante, les entiers)
- Types temporels (Les dates et les heures)
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
first_name = "Nhung"
last_name = "NGUYEN"
githubname = "https://github.com/nhungnguyen91"
puts first_name
puts last_name
puts github
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby

# Le résultat attendu est 52. 
a = 674
b=311
c=a%b
puts c
```



### 14. Qu'est-ce qu'une gem ? 

```texte
Une gems sont le modules de codes produits par d'autres développeurs qui apportent des fonctionnalités à l'application Ruby.
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
API est synonyme d’interface de programmation. Les APIs fonctionnent sur le accord de sorties et d’entrées. API permet de profiter des services des sites sans passer par l'interface graphique du site.

A pour Application : Ils peuvent être les applications qu'on utilise sur le smartphone ou un logiciel.
P pour Programmation : Les développeurs conçoivent les logiciels en utilisant les API
I pour Interface : On peut interagisser avec l’application.

On peut connecter à API en utilisant un HTTP POST simples et les clés d'APIs
```



### 16. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur

hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom

puts "Quel est votre prénom ?"
name = gets
time = Time.now
if time.hour <= 12
  puts "Bonjour " + name
else
  puts "Bonsoir " + name
end
```



### 15. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]

require 'bundler/inline'

gemfile true do
 source 'http://rubygems.org'
 gem 'twitter'
end

client = Twitter::REST::Client.new do |config|
  config.consumer_key        = "PFYhAJUwg1L249HxeRzuZBScI"
  config.consumer_secret     = "h1RKmEYzDvZrb7NgC5a9wxoMgopnf6lCAJxYUjF7DGlOjIGKP9"
  config.access_token        = "2311968372-DjLkns60QGjwgPshVyfHtBHPj4k0NzBytTphJc3"
  config.access_token_secret = "HPxR0y1ttuORtlKk63RgAlrQlsS2NzmEVpO9ZGTKnpWpG"
end

client = Twitter::REST::Client.new do |config|
  config.consumer_key        = "TACLÉTROPBIEN"
  config.consumer_secret     = "TACLÉTROPBIEN"
  config.access_token        = "TACLÉTROPBIEN"
  config.access_token_secret = "TACLÉTROPBIEN"
end

client.follow("richardbranson")
client.follow("jeffweiner")
client.follow("LinkedInQueen")
client.follow("ericschmidt")
client.follow("elonmusk")
client.follow("petecashmore")
client.follow("SteveForbesCEO")
client.follow("mtbarra")
```



### 16. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

