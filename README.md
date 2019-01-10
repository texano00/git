# git
Notes from my experiences

## Commit message format
* Short and direct to changes
* Who read this must immediately know the working area and the changes done
* Lowercase

```bash
<action>(<target>): <message>

<body>

<footer>
```

`<action>`
* test -> adding missing tests, refactoring tests; no production code change
* fix -> fixing on an existing object
* perf -> improving performance
* docs -> add/improve documentation
* chore -> updating grunt tasks etc, no production code change
* feat -> add a new feature
* refactor -> refactoring production code, eg. renaming a variable


`<target>` depends on the project in which we are working.
For an Ionic APP we can image:
* tabs
* home
* nav
* etc

`<message>`
* must be short and direct to the changes
* use the imperative; es. `add` not `added`

`<body>`
Like message but with more details; ex. List

`<footer>`
Reference to issue or breaking changes info

Example:

```bash
docs(infinite-scroll): usage docs

* Update readme.md
* Update readme.md
* Modifying readme for scrollInfinite in the right place

Closes #1223, #1224
```
