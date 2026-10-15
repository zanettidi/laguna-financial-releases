# Laguna Financial — instaladores

Gestão financeira pessoal: contas, movimentos, categorias, etiquetas, orçamentos, pagamentos planeados, objetivos, investimentos e estatísticas — com importação de extratos bancários (CSV), regras de categorização automática e cópias de segurança.

Este repositório tem só as versões publicadas. **Descarregue o instalador na [última release](https://github.com/zanettidi/laguna-financial-releases/releases/latest).**

## Instalar

Os instaladores trazem o Java e a base de dados incluídos — não é preciso instalar mais nada. Os dados ficam no seu computador, em `~/.laguna-financial` (no Windows, `C:\Users\<utilizador>\.laguna-financial`).

| Sistema | Ficheiro | Como instalar |
|---------|----------|---------------|
| macOS com Apple Silicon (M1, M2, M3…) | `Laguna.Financial-<versão>-apple-silicon.dmg` | Abrir e arrastar para Aplicações. |
| macOS com processador Intel | `Laguna.Financial-<versão>-intel.dmg` | Abrir e arrastar para Aplicações. |
| Windows | `Laguna.Financial-<versão>.msi` | Duplo clique. Instala só para o utilizador, sem pedir administrador. |
| Linux (Debian/Ubuntu) | `laguna-financial_<versão>_amd64.deb` | `sudo apt install ./laguna-financial_<versão>_amd64.deb` |

**Qual é o meu Mac?** Menu Apple (canto superior esquerdo) › **Acerca deste Mac**: se disser "Chip Apple M…", é Apple Silicon; se disser "Processador … Intel", é Intel. (Até à versão 1.3.0 só havia o `.dmg` para Apple Silicon, sem o sufixo no nome.)

Ao abrir, a aplicação abre no browser (`http://localhost:8081`) e fica um ícone na barra do sistema com **Abrir** e **Sair**. No primeiro uso, crie a conta em "Criar conta"; o guia **Primeiros passos** no Início ajuda a configurar o resto.

### Primeira abertura (instaladores sem assinatura)
- **macOS:** se disser que não pode verificar o programador, clique direito na aplicação › **Abrir** (ou Definições do Sistema › Privacidade e segurança › **Abrir mesmo assim**).
- **Windows:** no aviso do SmartScreen, **Mais informações** › **Executar mesmo assim**.

## Atualizar

Quando houver uma versão nova, a aplicação avisa no menu lateral ("Nova versão disponível"). Feche-a (ícone › **Sair**) e instale a versão nova por cima — os dados ficam. No Mac, escolha o `.dmg` do seu tipo de Mac (ver acima). Antes de cada atualização que mude a base, a aplicação guarda uma cópia em `.laguna-financial/backups/`.

## Cópias de segurança

Em Preferências › **Cópias de segurança**: fazer uma cópia agora, uma cópia automática por semana (ficam as 5 mais recentes) e restaurar qualquer cópia. Em Preferências › **Os seus dados** pode também exportar tudo num ZIP de ficheiros CSV.

Para levar os dados para outro computador, copie a pasta `.laguna-financial` com a aplicação fechada.
