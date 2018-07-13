# go_domain
This is a simple tool to find a domain available 


# Quick Start!
0. git clone this repository
```ruby:~
git clone https://github.com/EG-easy/go_domain.git
```
1. register https://words.bighugelabs.com/ and get APIKEY to find similar word

2. paste that APIKEY on ~/.bash_profile(for Mac) as bellow
```ruby:~
export BHT_APIKEY=abcdefghijk12345
```
3. start application
```ruby:~
cd domainfinder
sh build.sh
./domainfinder
```

4. Now you can put any English word, and that tools show you which domain is available


--------------------------------------------------------------------------------

# separate usage
You can also use the tools separately.
```ruby:~
cd available
go build -o available
./available
```
You can put domain like google.com, then the tool judge the domain is available or not.



