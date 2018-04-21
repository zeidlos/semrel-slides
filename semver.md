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



## Node Modules only?



## No! SemRel all the things!
[Example](https://github.com/semantic-release/cli/releases)



# Requirements for automation


## Proper commit messages


## Angular Commit Message Format
(You can use custom conventions as well)


```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

```
fix(navigation-controller): Fixes routing for modal views

Closes: #123
```


## commitizen
CLI to write commit messages according to a (custom) shared convention


## There are plugins for VSCode, Atom, Intellij, Sublime, ...


## semantic-release
Automates release based on commit messages


## JS Only?
Tooling is JS, but works for everything.



# Live Demo