# Resources

* [Android Intents with Chrome](https://developer.chrome.com/multidevice/android/intents)
* [Whitepaper – Attacking Android browsers via intent scheme URLs](http://www.mbsd.jp/Whitepaper/IntentScheme.pdf)
* [Deep App linking and changes to Chrome on Android](https://paul.kinlan.me/deep-app-linking-on-android-and-chrome/)

# Runnig Sinatra server

* Install [Homebrew](http://brew.sh/)
* Install [Ruby 2.2.0](https://www.ruby-lang.org/en/) with [rbenv](https://github.com/sstephenson/rbenv) 
* Install [Bundler](http://bundler.io/)
* **Install project dependencies with `bundle install` from `www` directory**
* Ensure that your server and device are on the same network
* Run server with `ruby server.rb`
* Check your server's ip with `ifconfig` and open the *homepage* on your device with `SERVER_IP:9494`
* Click the link and verify the behaviour
