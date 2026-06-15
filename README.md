# Extrair Resumos, Títulos e Palavras chave (TexTum)

Aplicativo Windows (executável) para separar, extrair metadados e organizá-los automaticamente num único arquivo .txt pronto para usar em IraMuTeQ. 

## Download (Windows)
Baixe a versão mais recente em **Releases**:
- Baixe o arquivo `extrair_corpus.exe` 

## Como usar (sem instalar nada)
1. Execute `extrair_resumos.exe`
3. Selecione a pasta com os PDFs
4. Clique em **Gerar Corpus**
5. O programa gera o arquivo de saída na pasta em que estão os pdfs

## O que o programa faz
- [extrai texto/metadata de PDFs]
- [limpa/normaliza]
- [gera `.txt` UTF-8 com delimitadores `**** *arquivo`]
- [logs/relatório, se existir]


## Problemas comuns
### Windows bloqueou / SmartScreen
Se aparecer “Windows protegeu o seu PC”:
- Clique em **Mais informações** → **Executar assim mesmo**
- Se for o caso, clique em adicionar exceção

### Antivírus sinalizando como suspeito
Alguns antivírus podem gerar falso positivo em executáveis empacotados.
- Se isso ocorrer, baixe novamente pela página de Releases e permita exceção.
