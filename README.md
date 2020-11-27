# ApexPMD
This is my personal configuration for using ApexPMD static code analysis with my customized set of rules

### Setup
- Download [ApexPMD VS Code Extension](https://marketplace.visualstudio.com/items?itemName=chuckjonas.apex-pmd)
- Clone this Repo
- VS Code => Settings:
```
"apexPMD.additionalClassPaths": [
    "*/Users/userName/folders*/apexPMD"
],
"apexPMD.rulesets": [
    "*/Users/userName/folders*/apexPMD/customApexRules_PMD.xml"
]
```
