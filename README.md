# Laguna Financial — instaladores

Gestão financeira pessoal: contas, movimentos, categorias, etiquetas, orçamentos, pagamentos planeados, objetivos, investimentos e estatísticas.

Este repositório tem só as versões publicadas. **Descarregue o instalador na [última release](https://github.com/zanettidi/laguna-financial-releases/releases/latest).**

## Instalar

Os instaladores trazem o Java e a base de dados incluídos — não é preciso instalar mais nada. Os dados ficam no seu computador, em `~/.laguna-financial` (no Windows, `C:\Users\<utilizador>\.laguna-financial`).

| Sistema | Ficheiro | Como instalar |
|---------|----------|---------------|
| macOS (Apple Silicon) | `Laguna.Financial-<versão>.dmg` | Abrir e arrastar para Aplicações. |
| Windows | `Laguna.Financial-<versão>.msi` | Duplo clique. Instala só para o utilizador, sem pedir administrador. |
| Linux (Debian/Ubuntu) | `laguna-financial_<versão>_amd64.deb` | `sudo apt install ./laguna-financial_<versão>_amd64.deb` |

Ao abrir, a aplicação abre no browser (`http://localhost:8081`) e fica um ícone na barra do sistema com **Abrir** e **Sair**. No primeiro uso, crie a conta em "Criar conta".

### Primeira abertura (instaladores sem assinatura)
- **macOS:** se disser que não pode verificar o programador, clique direito na aplicação › **Abrir** (ou Definições do Sistema › Privacidade e segurança › **Abrir mesmo assim**).
- **Windows:** no aviso do SmartScreen, **Mais informações** › **Executar mesmo assim**.

## Atualizar

Quando houver uma versão nova, a aplicação avisa no menu lateral ("Nova versão disponível"). Feche-a (ícone › **Sair**) e instale a versão nova por cima — os dados ficam. Antes de cada atualização que mude a base, a aplicação guarda uma cópia em `.laguna-financial/backups/`.

Para levar os dados para outro computador, copie a pasta `.laguna-financial` com a aplicação fechada.
