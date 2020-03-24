<h1 align="center">Members-Only 👋</h1>

<img src="https://i.ibb.co/YXCTpxw/Screenshot-from-2020-03-24-17-00-20.png" alt="Screenshot-from-2020-03-24-17-00-20" border="0">

## About the project
This project is written as an exclusive clubhouse, where your members can write embarrassing posts about non-members. Inside the clubhouse, members can see who the author of a post is but, outside, they can only see the story and wonder who wrote itfocused on user authentication and privileges. The key concepts are the use of a secure password digest method, a browser cookie 'remember user login' method (with secure remember token digest), and limiting access to certain functions (esp: viewing post author names) to signed-in users only. 

## Built With
* Ruby on Rails

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```$ bundle install --without production```

Next, migrate the database:

```$ rails db:migrate```

Finally, run the server:

```$ rails server```

You can open application in your browser:

```http://localhost:3000/```

### Testing project
* Run tests

```sh
rails test
```

## Authors

👤 **Tunde Oretade**
   - Github: [@tundeiness](https://github.com/tundeiness)
   - LinkedIn: [Tunde Oretade](https://www.linkedin.com/in/tundeoretade/)
   
👤 **Olga Pelts**
   - Github: [@pelzolga123](https://github.com/pelzolga123)
   - LinkedIn: [Olga Pelts](https://www.linkedin.com/in/olga-pelts/)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/pelzolga123/members-only/issues).

1. Fork it (https://github.com/pelzolga123/members-only/fork)
2. Create your working branch (git checkout -b [choose-a-name])
3. Commit your changes (git commit -am 'what this commit will fix/add')
4. Push to the branch (git push origin feature/[feature-name])
5. Create a new Pull Request
