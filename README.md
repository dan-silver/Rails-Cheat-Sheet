Rails-Cheat-Sheet
=================

## Rails Generate Examples
#### Create a Resource
	rails generate scaffold Post name:string title:string content:text

#### Generate Models
	rails generate model Post title:string body:text published:boolean

#### Add Column to Existing Model
	rails generate migration AddFieldToModel field:type


## Database
#### Update to Latest Migration
	rake db:migrate

#### Delete Database
	rake db:drop

#### Create Database
	rake db:create

#### Column Types
	:primary_key, :string, :text, :integer, :float, :decimal, :datetime, :timestamp, :time, :date, :binary, :boolean
