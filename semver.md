## Semantic Versioning &amp; Automatic Changelog done right
One approach on how to take the headache out of release management



# Intro
Version numbers should follow a certain, standardised scheme in order to make sense to humans and software


# Semantic Versioning
[semver.org](https://semver.org/)


* **MAJOR** Breaking changes!
* **MINOR** Feature release
* **PATCH** Bugfix release
Angular **5.2.10**


## Semver vs. Marketing Releases

* Semver exposes an 'API' to developers and non-technical people
* Dependency-Management


```
"dependencies": {
    "@octokit/rest": "15.2.x",
    "axios": "0.x",
    "async": "x"
}
```


```
"fancy-kitten-library": "x"     // Gimme the new shit!
"fancy-kitten-library": "2.x"   // Allows new features
"fancy-kitten-library": "2.1.x" // Fixed to Bugfixes
"fancy-kitten-library": "2.1.0" // Fixed Version
```


## Why should I use it?
* Communicate changes clearly
* Allow for clean dependency management
* Stop worrying about versioning



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
