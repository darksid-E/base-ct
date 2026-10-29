# base-ct

Base portátil do **Dashboard PI** (Central de Dados Coqueria): Python 3.12 para Windows 64 bits com as
bibliotecas de código aberto que o dashboard usa, já instaladas. Não precisa instalar Python nem pip.

> Este repositório tem **só** Python e bibliotecas públicas. O código do dashboard e qualquer informação
> interna ficam fora daqui (são baixados pelo Gestão Coqueria, com login).

## Download

Veja a última versão em **Releases** → `DashboardPI-base-vN.zip`.

## Como usar

1. Extraia a pasta `DashboardPI` em `C:\Users\<usuário>\` (fora do OneDrive).
1. Baixe o pacote do dashboard no Gestão Coqueria (Relatório de Turno → Dashboard PI) e deixe em Downloads.
1. Abra `Abrir Dashboard PI.bat`.

## Conteúdo da base v1

- Python 3.12.16 (CPython, build [python-build-standalone](https://github.com/astral-sh/python-build-standalone) 20261026), x86_64 Windows
- streamlit 1.66.1, pandas 3.1.0, plotly 7.1.0, numpy 2.5.4, pyarrow 26.0.0, requests 2.34.2,
  requests-kerberos 0.15.0, pyspnego 0.12.4 (+ sspilib), tzdata e dependências — lista completa em `bibliotecas-versoes.txt`

## Licenças

Python: PSF License (`python/LICENSE.txt`). Cada biblioteca mantém a própria licença em
`python/Lib/site-packages/<biblioteca>.dist-info/`.
