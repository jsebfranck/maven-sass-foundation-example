# maven-sass-foundation-example

Example of Foundation project (http://foundation.zurb.com/docs/sass.html) compiled with Maven.

src/main/sass directory has been created by the following command :

```
compass create -r zurb-foundation --using foundation
```

## To compile CSS

With compass (works) :

```
cd src/main/sass
compass compile
```

With maven (doesn't work yet) :

```
mvn clean compile
```
