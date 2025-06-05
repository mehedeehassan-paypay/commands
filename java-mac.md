

### add open jdk
```
brew install openjdk@21
```
### search openjdk location
```
brew --prefix openjdk
```


#### java home
```
/usr/libexec/java_home -V
```

```
 jenv add /usr/local/Cellar/openjdk@21/21.0.7/libexec/openjdk.jdk/Contents/Home
```
res
```
openjdk64-21.0.7 added
21.0.7 added
21.0 added
 21.0.7 already present, skip installation
```

```
jenv global 21.0.7
```
https://ymkfelix.medium.com/how-to-set-up-multiple-java-versions-on-a-macbook-8bae41345f72



