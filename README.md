# Sample_RockRecords_RoR

Alamo Records is a online store that sells vintage vinyl records. It is built on the [Ruby on Rails](http://www.rubyonrails.org) web framework and consists of the following models:

1. Publisher - a publisher sells albums.
2. Album - albums are sold by publishers and include many songs.
3. Song - a song is recorded onto one album. It is written by one artist.
4. Artist - an artist writes songs.

## Require version

1. Ruby -2.4.6
2. Rails - 4.2.11
3. sqlite3 - 1.3.13
4. bundler - 1.17.3

## Step to run the application

Go to project directory run the following command step by step:

1. bundle install
2. bundle exec rake db:create
3. bundle exec rake db:migrate
4. bundle exec rake db:seed
5. rails s 

Rails server started with port 3000. open your browser and hit http://localhost:3000/

## Relationships between models is represented in the following diagram:

![Rock Records model diagram](public/alamo_records_diagram.png)


## API
(http://localhost:3000/swagger)