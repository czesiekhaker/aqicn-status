# aqicn-status

Program for pulling air quality information from
[aqicn.org](http://aqicn.org).

# Requirements

* Python 3
* `termcolor` module

# Usage

```
$ ./air_quality 'sarajevo bjelave'
Air quality in Sarajevo Bjelave is Moderate (55)
Updated 2017-01-15 02:00:00
More info: http://aqicn.org/city/bosnia-herzegovina/sarajevo/bjelave
```

```
$ ./air_quality krakow
Air quality in Kraków-ul. Dietla, Małopolska is Good (48)
Updated 2017-01-15 00:00:00
More info: http://aqicn.org/city/poland/malopolska/krakow-ul.-dietla
```

```
$ ./air_quality warsaw            
Air quality in Marszałkowska, Warszawa, Mazowieckie is Unhealthy for
Sensitive Groups (115)
Updated 2017-01-15 00:00:00
More info: http://aqicn.org/city/poland/mazowieckie/warszawa/marszalkowska
```

# Known bugs

* errors out if no places are found
