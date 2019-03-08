# Task17DataHibernate

## GET options
*Use Body none*

### GET...    
`/users` to get all users.
e.g. 'http://localhost:8080/users'

`/user{id}` to get user by ID number.
e.g. 'http://localhost:8080/user/1'

`/characters` to get all characters.
e.g. 'http://localhost:8080/characters'

`/character/{id}` to get character by ID number.
e.g. 'http://localhost:8080/characters'

`/classes` to get all classes.
e.g. 'http://localhost:8080/classes'

`/class/{className}` to get class by class name.
e.g. 'http://localhost:8080/class/druid'


## POST options
*Use Body content type: application/json*

### POST...
`/user` to add new user.    
e.g.    
```
{
"userName" : "Thomas",
"userEmail" : "thomas@gmail.com",
"userPassword" : "mittPassord"
}
```

`/character` to add new character.
e.g.
```
{
"userID" : 9,
"characterName" : "PalaCraig",
"className" : "Paladin",
"characterLvl" : 8
}
```
