
## VS Code Next Level
---

<details>
<summary>Disclaimer</summary>
- Not a training but awareness
</details>

<details>
<summary>Install and PS 5.1</summary>

- ```choco install vscode -y```
- [Set VS Code for PS 5.1](https://aarons.atlassian.net/wiki/spaces/DBA/pages/2818408460/How+to+set+VS+Code+for+PowerShell+5.1)
- No further development in ISE
- VS Code
  - Open Source
  - extensions
    - support multiple languages
  - integration
    - Git
    - Azure
    - ADS
</details>

<details>
<summary>Themes and Extensions</summary>

- ISE theme
- PowerShell extension pack
- Git
- Azure
- markdown
</details>

<details>
<summary>Shorcuts and code editing</summary>

- Command Pallette
  - \>
- screencast mode
- ctrl `
- ctrl ,
- ctrl B
- ctrl E
- code and file name (code C:\Ravi\Languages\Demo\NextLevelVSCode\Test.ps1)
- alt + arrow move the line
- alt shift + arrow  to copy the line
- ctrl x (no highlighting needed)
- multi line comment
  - ctrl L /
- Ctrl W
- Ctrl N


</details>

<details>
<summary>Snippets</summary>
- PS function
- loop
- invoke-sqlcmd
</details>

<details>
<summary>Settings </summary>

- command ,
- mini map
- font
</details>

<details>
<summary>Settings sync</summary>

- sync
</details>

<details>
<summary>Git</summary>

- Git ignore
- `git clone https://github.com/ravilobo/NextLevelVSCode.git`
</details>

<details>
<summary>debug</summary>

- debug
</details>

<details>
<summary>Intellisense in the Terminal</summary>

```
install-module psreadline -Force
Set-PSReadLineOption -PredictionSource History
```
</details>



<details>
<summary>RegEx</summary>

```
C0724
C1108
C1430
C1847
C0537
C0563
C1024
C0331
C6006
F982
```
```
SELECT *
FROM agreement
where sourcestore in (
'C0724','C1108','C1430','C1847','C0537','C0563','C1024','C0331','C6006','F982'
)
```

</details>

<details>
<summary>Highly customizable</summary>

- mini map
- debug
- resize terminal
</details>
<details>
<summary>Reference</summary>

- [Visual Studio Code Crash Course](https://www.youtube.com/watch?v=WPqXP_kLzpo&list=PLH6KG78VMXz7I8RA7FtiUUT0g-5HQqePM&index=11)
- [Optimizing Visual Studio Code for Powershell Development](https://www.youtube.com/watch?v=9uMorgBB_RU&list=PLH6KG78VMXz7I8RA7FtiUUT0g-5HQqePM&index=10)
</details>


