# Members-Only

This project is written as an exclusive clubhouse, where your members can write embarrassing posts about non-members. Inside the clubhouse, members can see who the author of a post is but, outside, they can only see the story and wonder who wrote itfocused on user authentication and privileges. The key concepts are the use of a secure password digest method, a browser cookie 'remember user login' method (with secure remember token digest), and limiting access to certain functions (esp: viewing post author names) to signed-in users only. 

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```$ bundle install --without production```

Next, migrate the database:

```$ rails db:migrate```

Finally, run the server:

```$ rails server```

You can open application in your browser:

```http://localhost:3001/```


## Contributors

* [Tunde Oretade](https://github.com/tundeiness)
* [Olga Pelts](https://github.com/pelzolga123)
