# exante.eu FIX44
This repository contains FIX (Financial Information eXchange) API Data dictionary, Field classes and Message Factory for Exante broker (https://exante.eu) you can use in your QuickFIX/J project

EXANTE is a International investment services company established in 2011 that offers global multi-asset financial services, including direct access to a wide range of financial markets in the US, European Union and Asia-Pacific. EXANTE provides online trading access to over 50 markets worldwide.

More info about FIX protocol: https://en.wikipedia.org/wiki/Financial_Information_eXchange

QuickFIX/J: 100% Java Open Source FIX Engine

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
