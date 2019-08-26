## battlesnake-go

A simple [Battlesnake AI](http://battlesnake.io) written in Go.

Visit [https://github.com/battlesnakeio/community/blob/master/starter-snakes.md](https://github.com/battlesnakeio/community/blob/master/starter-snakes.md) for API documentation and instructions for running your AI.

### Developing and Deploying with Gitpod

Gitpod lets you get started in a fully setup and sandboxed environment.

1. click the Gitpod button below. <br>
[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/battlesnakeio/starter-snake-go)
1. You will need to sign in with a GitHub account, and it will create an online workspace for you.
1. Run `make run` in the terminal. 
1. When it notifies you that the app is running on port 9000, click on `Open Browser`.
      - The url that it goes to is your snake's url (enter it in when you add your snake to play.battlesnake.io).

IMPORTANT: When the tournament starts, make sure that your workspace is active! It times out after 30 minutes (10 minutes if the tab is closed), and your snake will be turned off!

### Fork this repo

If you want to save your changes, you'll need to push them to your own repo. 

1. [Fork this repo](https://github.com/battlesnakeio/starter-snake-go/fork).

1. Push to your new repo (fill in `<your-username>` with your GitHub username)
```
mkdir -p $GOPATH/go/src/github.com/battlesnakeio
cd $GOPATH/go/src/github.com/battlesnakeio
git clone https://github.com/battlesnakeio/starter-snake-go 
cd starter-snake-go
git remote set-url origin https://github.com/<your-username>/starter-snake-go
git push
```

### Running tests locally

```
make test
```

### Deploying to Heroku instead of Gitpod

You'll need:
  1. A working Go development environment ([guide](https://golang.org/doc/install)).
  1. Read [Heroku's guide to deploying Go apps](https://devcenter.heroku.com/articles/getting-started-with-go#introduction) <br>
[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)
1. [Fork](#fork-this-repo) or clone this repo 
1. Create a new Go Heroku app using Go buildpack.<br>
`
heroku create
`
1. Push code to Heroku servers.<br>
`
git push heroku master
`
1. Open Heroku app in browser.<br>
`
heroku open
`
Or go directly via http://APP_NAME.herokuapp.com
1. View/stream server logs.<br>
`
heroku logs --tail
`

### Questions?

[Email](mailto:battlesnake@sendwithus.com), [Twitter](http://twitter.com/send_with_us)
