# Player Score

This is a simple API built in Rails that manages User's scores.


## How to use?
1. cd player_score 
2. bundle install
3. rails db:setup

## Start App
   rails s


## App Routes

```
scores
   GET		/scores		scores#index	Query score list (Customized Query)
   POST		/scores		scores#create	Create a new score record
   GET		/scores/:id	scores#show	Query single score record
   DELETE	/score/:id	scores#destroy	Delete single score record

users
   GET		/users		users#index	Query user list
   GET		/users/:id	users#show	Query user record 
```