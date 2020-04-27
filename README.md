# exante.eu FIX44
This repository contains FIX (Financial Information eXchange) API Data dictionary, Field classes and Message Factory for Exante broker (https://exante.eu) you can use in your quickfixj project

More info about FIX protocol: https://en.wikipedia.org/wiki/Financial_Information_eXchange

# Usage
1. Clone the repo
```
git clone git@github.com:mtsatsenko/exantefix44.git
```
2. Build it
```
$ cd exantefix44 && mvn package
```
3. import resulting `field` and `messages` packages in place of standard quickfixj ones
```java
import com.github.mtsatsenko.exantefix44.field;
import com.github.mtsatsenko.exantefix44.messages;
```
