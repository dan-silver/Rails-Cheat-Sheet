Rails-Cheat-Sheet
=================
## Quickly generate rails app with [composer](https://github.com/RailsApps/rails-composer)
```rails new app-name -m https://raw.github.com/RailsApps/rails-composer/master/composer.rb```

## Rails Generate Examples
#### Create a Resource
	rails generate scaffold Post name:string title:string content:text

#### Generate Models
	rails generate model Post title:string body:text published:boolean

#### Add Column to Existing Model
	rails generate migration AddFieldToModel field:type


## Database
#### Initial database setup
	rake db:setup

#### Update to Latest Migration
	rake db:migrate

#### Delete Database
	rake db:drop

#### Create Database
	rake db:create

#### Column Types
	:primary_key, :string, :text, :integer, :float, :decimal, :datetime, :timestamp, :time, :date, :binary, :boolean

## Environmental Variables
#### Upload environmental variables to Heroku with [figaro](https://github.com/laserlemon/figaro)
	rake figaro:heroku

## Cloud Hosting
####  Launch server with public IP
	rails s --binding=PUBLIC_IP_ADDRESS
