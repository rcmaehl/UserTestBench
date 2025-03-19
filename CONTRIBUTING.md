## Coding Guidelines

* Use CamelCase variables
* Tabs, not spaces, with tab width set to 4
* Tidy code with Tidy.exe before you create PR
* Use Au3Check.exe for pre check code before you create PR
* Follow https://www.autoitscript.com/wiki/Best_coding_practices

## Pull Request Guidelines

### ALL PRs
* One "change" per pull request
    * *Updated Dependancies of All Benches needing X* is okay
    * *Updated Bench X and Updated Related Includes files* is okay
    * *Updated Bench X, Results Previs, UI Icon Colors* is NOT okay
* External DLLs, EXEs, and other executables may not be included
* The Pull Request title must give a brief overview of the change

### ALL Code Changes
* Place any Function Information above Function
* Ideally use *Make UDF Header* function in SciTE
    * Other headers are fine but will be converted

### GUI Changes
* Include before and after screenshot

### WMIC Changes
* All WMIC calls must be cached using Static Variables
