# Mapeamento MITRE ATT&CK (v12) — REvil

| Tática | Técnica | Sub-técnica | Procedimento |
|---|---|---|---|
| Defense Evasion, Privilege Escalation | T1134 Access Token Manipulation | .002 Create Process with Token | Executa a si mesmo com privilégios administrativos via `runas` |
| Command and Control | T1071 Application Layer Protocol | .001 Web Protocols | HTTP/HTTPS na comunicação com o C2 |
| Execution | T1059 Command and Scripting Interpreter | .005 Visual Basic | Macros VBA ofuscadas |
| Impact | T1486 Data Encrypted for Impact | — | Criptografa arquivos e exige resgate |
| Defense Evasion | T1140 Deobfuscate/Decode Files or Information | — | Decodifica strings e payloads criptografados |
