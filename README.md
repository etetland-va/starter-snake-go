## battlesnake-go

A simple [Battlesnake AI](http://battlesnake.io) written in Go.

Visit [https://github.com/battlesnakeio/community/blob/master/starter-snakes.md](https://github.com/battlesnakeio/community/blob/master/starter-snakes.md) for API documentation and instructions for running your AI.

To get started, click the button below. You will need to sign in with a GitHub account, and it will create an online workspace for you.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/ert485/starter-snake-go)

After that, run `make run` in the terminal. When it notifies you that the app is running on port 9000, click on `Open Browser`. The url that it goes to is your snake's url (enter it in when you add your snake to play.battlesnake.io).

When the tournament starts, make sure that your workspace is active! It times out after 30 minutes (10 minutes if the tab is closed), and your snake will be turned off!

### Fork this repo

1. [Fork this repo](https://github.com/battlesnakeio/starter-snake-go/fork).

1. Push and Pull from your new repo
```
git clone https://github.com/battlesnakeio/starter-snake-go $GOPATH/go/src/github.com/battlesnakeio/starter-snake-go
cd $GOPATH/go/src/github.com/battlesnakeio/starter-snake-go
git remote set-url origin https://github.com/<your-username>/starter-snake-go
```

### Running tests locally

```
make test
```

### Deploying to Heroku instead of Gitpod

You'll need:
  1. A working Go development environment ([guide](https://golang.org/doc/install)).
  1. Read [Heroku's guide to deploying Go apps](https://devcenter.heroku.com/articles/getting-started-with-go#introduction)

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)


Note: if you're missing any packages, use `make get`.

1) Create a new Go Heroku app using Go buildpack.
```
heroku create
```

2) Push code to Heroku servers.
```
git push heroku master
```

3) Open Heroku app in browser.
```
heroku open
```
Or go directly via http://APP_NAME.herokuapp.com

4) View/stream server logs.
```
heroku logs --tail
```

### Questions?

[Email](mailto:battlesnake@sendwithus.com), [Twitter](http://twitter.com/send_with_us)
