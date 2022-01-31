# Comandos úteis rails

# Rodando projeto:

```ruby
bin/rails server
```

# Gerando controller por linha de comando

```ruby
bin/rails generate controller Articles index --skip-routes
```

> skip routes ignora a criação de rotas, tendo que criar na mão posteriormente

# Gerando model com atributos

```ruby
bin/rails generate model Article title:string body:text
```

# Rodando migrations

```ruby
bin/rails db:migrate
```

# Abrir console do DB

```ruby
bin/rails console
```
