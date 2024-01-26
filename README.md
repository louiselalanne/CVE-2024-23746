# CVE-2024-23746
Miro Desktop 0.8.18 on macOS allows Electron code injection.

## PoC 
signature and version:
![Captura de Tela 2024-01-26 às 09 41 42](https://github.com/louiselalanne/CVE-2024-23746/assets/100588945/35b8d8c5-2334-4a47-899e-9b5b248faa15)

tool used to explore the vulnerability:
https://github.com/r3ggi/electroniz3r

verify if is vulnerable:
![Captura de Tela 2023-12-12 às 11 19 02](https://github.com/louiselalanne/CVE-2024-23746/assets/100588945/3671fc52-7d83-44ff-8b87-cab43828e3d1)

inject a Blind Shell:
![Captura de Tela 2023-12-12 às 11 19 25](https://github.com/louiselalanne/CVE-2024-23746/assets/100588945/30610c82-e8b7-4bd6-8301-f80481de1efe)

## References
https://book.hacktricks.xyz/macos-hardening/macos-security-and-privilege-escalation/macos-proces-abuse/macos-dirty-nib
https://www.notion.so/web-clipper
