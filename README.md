# 🛡️ CTI Report: Kaseya VSA Ransomware Attack (REvil/Sodinokibi)

> **Nota:** Relatório analítico de Cyber Threat Intelligence (CTI) focado no ataque de *Supply-Chain* contra a Kaseya efetuado pelo grupo REvil em julho de 2021. Projeto analítico acadêmico/fictício baseado no cenário real.

---

# Relatório de CTI — Ataque supply-chain à Kaseya (REvil/Sodinokibi)

Relatório analítico de **Cyber Threat Intelligence** produzido como exercício acadêmico (**cenário fictício**: cliente "John Doe – Serviços Financeiros", RFI 2023-9012001; o "grau de sigilo reservado" é simulado). Os fatos analisados, porém, são do incidente real de julho de 2021.

- **Relatório:** nº 001/2024 — Grupo 6, ACADI-TI
- **Data:** 05/05/2024
- **Autor:** Marco Aurelio Cruz

## Requisitos de inteligência

1. Identificar o adversário envolvido no ataque contra a Kaseya
2. Avaliar o incidente de meados de 2021 e confirmar se ocorreu
3. Levantar TTPs e a vulnerabilidade explorada para apoiar a defesa

## Resumo

Em 2 de julho de 2021, o grupo de ransomware como serviço **REvil** explorou uma falha no **Kaseya VSA** (CVE-2021-30116, bypass de autenticação e execução de comandos) e distribuiu o ransomware por uma falsa atualização a clientes de provedores gerenciados (MSPs). Estima-se cerca de 1.500 empresas afetadas, e o grupo exigiu US$ 70 milhões. O DIVD havia reportado as falhas à Kaseya antes do ataque. Os sites do REvil saíram do ar em 13/07/2021.

## Conteúdo

```
├── report/
│   └── Relatorio-CTI-001-2024-Kaseya-REvil.pdf   # relatório completo (11 páginas)
├── iocs/                                          # hashes, IPs, CVEs, registro
└── mitre_attack.md                                # TTPs mapeados no ATT&CK
```

## Principais tópicos do relatório

Sumário executivo, avaliação, lacunas de inteligência, mapeamento MITRE ATT&CK, cronograma (02/07/2021 a 26/07/2021), IOCs, assinaturas (YARA) e metadados de vítimas/setores.

## Fontes

CNET, BBC News, WeLiveSecurity, CSO, Picus Security, DIVD CSIRT, Talos, Huntress.

## Aviso

Material educacional. Os IOCs são de 2021 e devem ser validados antes de uso operacional.
