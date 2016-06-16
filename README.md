## Socialist

Socialist es una red social de código abierto escrita usando el Ruby on Rails.

¿Quieres verla en acción? Aquí está en vivo, subida a Heroku [http://socialist-db.herokuapp.com](http://socialist-db.herokuapp.com)

### ¿Qué usa?

* [Ruby on Rails 4.1.6](https://github.com/rails/rails) 
* [Bootstrap](https://github.com/twbs/bootstrap-sass)
* [Devise](https://github.com/plataformatec/devise)
* [Public Activity](https://github.com/chaps-io/public_activity)


### ¿Como la inicio?

Instalas Ruby on Rails, clonas el repositorio:
  
```
git clone https://github.com/alexisllamas/Socialistest.git
cd Socialistest
```
Instalas las dependencias usando bundle:

```
bundle install
```

Corres las Migrations:

```
rake db:migrate
```

Prenses rails usando:

```
rails server
```

### Popular la base de datos
Para testearla puedes usar esta gema:

```
rake fill:data
```


### Pull Requests

* Fork este repo 
* Haz cambios
* Envíamelos y yo los reviso

### Issues
Si encuentras algún problema, repórtamelo por aquí.

