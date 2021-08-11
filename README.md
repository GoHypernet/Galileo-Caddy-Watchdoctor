[![alt](galileo_pres.png)](https://hypernetlabs.io/galileo)

# What it does

This is a go-based Caddy server plugin designed for use with the Galileo platform. Mission frameworks using Caddy can use the watchdoctor directive to get automatic notifications about processes they are running. 

# How to build

```
xcaddy build --with github.com/GoHypernet/Galileo-Caddy-Watchdoctor@v0.1.1
```

# How to use

See the included Caddyfile for an example of this directive's usage.

The first parameter is watch interval, the second is the timeout duration, third is nitificaiton server, the for parameter
is a list of servers to watch. 
