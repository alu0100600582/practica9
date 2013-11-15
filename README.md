# GemaMatriz

Gema para la implementación de matrices dispersas y densas, junto con las operaciones aritméticas más significativas.

## Installation

Add this line to your application's Gemfile:

    gem 'GemaMatriz'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install GemaMatriz


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request


##Jerarquía de clases

La jerarquía de clases propuesta será la siguiente:

Superclase abstracta Matriz, de la cual heredan los métodos:

mostrar

+

-

*

Clases derivadas:

MatrizDensa

MatrizDispersa

Ambas clases heredan de la superclase Matriz, y redefinen los métodos anteriormente especificados.
