
# It's Magic!
## Smart Versioning &amp; Automatic Changelog


## Warum?
* Aussagekr&auml;ftige Versionsnummern
* Standardisierte Definition


## Definition
MAJOR.MINOR.PATCH


* MAJOR wenn die Abw&auml;rtskompatibilit&auml;t kaputt geht (Breaking changes)
* MINOR wenn neue Features implementiert wurden
* PATCH wenn Bugfixes ver&ouml;ffentlicht werden


## Semver vs. StarMoney 11

* Semver Versionen sind keine Produktbezeichnungen oder gut f&uuml;rs Marketing.
* Semver hilft Entwicklern und PO's zu verstehen, wie und was sich ver&auml;ndert hat.
* Dependency-Management


## JavaScript &Ouml;kosystem
* Viele, viele, viele kleine Pakete
* Dependency H&ouml;lle


```
"dependencies": {
    "@octokit/rest": "^15.2.2",
    "async": "x",
    "axios": "^0.x",
    "babel-core": "^6.26.0",
}
```


## Wie sorge ich sinnvoll f&uuml;r Updates, ohne etwas kaputt zu machen?

* "cz-conventional-changelog": "x"
* "cz-conventional-changelog": "2.x"
* "cz-conventional-changelog": "2.1.x"
* "cz-conventional-changelog": "2.1.0"


## Fazit

Dependency-Management funktioniert nur, wenn die Package-Maintainer sich nach SemVer richten.

SemVer macht f&uuml;r alle Software-Produkte Sinn.


# Automatisierung


## Angular Commit Message Format

```
fix(navigation-controller): Fixes routing for modal views

Closes: #123
```


## commitizen


## semantic-release
