afterburner.fx
==============

The opinionated just-enough-framework (2 classes) MVP for JavaFX

afterburner.fx provides:

1. "Zero-Configuration" javax.inject.Inject DI of models and services
2. Convention-based unification of presenter, view, FXML and css.
3. Conventional resource bundle loading.
4. Afterburner is a "Just-Enough-Framework" extracted from [airhacks-control](https://github.com/AdamBien/airhacks-control) and used in [airpad](https://github.com/AdamBien/airpad) applications

The use of afterburner.fx is demonstrated in [https://github.com/AdamBien/followme.fx](https://github.com/AdamBien/followme.fx)

Jumpstart with:

```shell
mvn archetype:generate -Dfilter=com.airhacks:igniter
```



Afterburner is also available from maven central:
```xml
        <dependency>
            <groupId>com.airhacks</groupId>
            <artifactId>afterburner.fx</artifactId>
            <version>1.3</version>
        </dependency>
```
The current development version is available as snapshot:

```xml
        <dependency>
            <groupId>com.airhacks</groupId>
            <artifactId>afterburner.fx</artifactId>
            <version>1.4-SNAPSHOT</version>
        </dependency>
```

See also: [http://afterburner.adam-bien.com](http://afterburner.adam-bien.com)
