# Configuração Sofle V2.1 com Vial

Minhas configurações personalizadas para o teclado Sofle V2.1 usando Vial-QMK.

## Como usar

1. Clone este repositório
2. Os arquivos compilados são gerados automaticamente nos releases
3. Baixe o arquivo `.hex` mais recente e faça o flash no seu teclado
4. Configure seu layout usando o app Vial

## Vantagens do Vial

- ✅ Configuração em tempo real via GUI
- ✅ Não precisa recompilar para mudar layout
- ✅ Suporte a macros, tap dance, combos
- ✅ Rotary encoder configurável

## Compilação local

```bash
qmk compile -kb sofle -km vial
```