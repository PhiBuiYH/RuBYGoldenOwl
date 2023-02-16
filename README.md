# README

This README would normally document whatever steps are necessary to get the
application up and running.

* Download sourcecode : git clone https://github.com/PhiBuiYH/RuBYGoldenOwl.git
* Then : 
bundle install 
* rails db:migrate
* rails s 


* Create model and controller : 
* rails g scaffold product name description:text price:decimal image:string
* rails g controller cart show
* rails g model cart
* rails g model orderable product:belongs_to cart:belongs_to quantity:integer


Things you may want to cover:
install RVM
Install Ruby
* Ruby version : 3.1.2
* Rails version : 7.0.4
* Database : SQLite3 

