# Simple golang Web Application

I built this web application using [this](https://medium.com/google-cloud/building-a-go-web-app-from-scratch-to-deploying-on-google-cloud-part-1-building-a-simple-go-aee452a2e654) tutorial by Martin Ombura Jr.

### Prerequisites

* You will need to install go on your computer. See the [golang install documentation](https://golang.org/doc/install).
* Set your `$GOPATH` variable. There are good instructions for how to do this [here](https://github.com/golang/go/wiki/SettingGOPATH).
* Make sure you have a `go/src/github.com` directory. You can create one by changing into your go directory with `cd $GOPATH`, and then make the directories `mkdir -p src/github.com`.


### Running the web app from your computer

* Change into your github directory with `cd go/src/github.com`
* Clone this repo with `git clone git@github.com:kimschles/go-web-application.git` 
* Change into the `go-web-application` directory
* Run the server with `go run main.go`
* Open the app in your browser at `http://localhost:8080`
* If you want to have the app greet a specific name, add the name query at the of the url. For example, `http://localhost:8080/?name=Kim` 
* Stop the application with `ctl+C` 
