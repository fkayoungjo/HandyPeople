## HandyPeople

HandyPeople is a rails web app in which a user can find a handyperson to perform a particular service. We start by creating an account. Once inside the site we can request a multitude of services and rate the service person.

## Getting Started
![Image description](/Users/jordansimon/Downloads/HandyPeople/Screen Shot 2019-04-01 at 12.03.37 PM.png)
To begin using fork and clone the project. CD into  project folder. Use rake to create and migrate the database. Use rails start to server.

```
bash
rake db: create
```

```
bash
rake db: migrate
```

```
bash
rake db: seed
```

```
bash
rails start
```

## Usage

```
<% @handies.each do |handy| %>
  <li><%= link_to handy.name, handy_path(handy) %></li>
<% end %>
```

## Built With

Ruby on Rails,
HTML,
CSS,
MySQL

## Authors

Jordan Simon - Initial Work,
Mendy Cohen - Initial Work

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Demo
https://youtu.be/JAmja5Dp69k
