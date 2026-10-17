# Assinador do AdvBraz

O programa que o **AdvBraz** usa para assinar petições com o seu certificado digital
quando ele é um **token A3, um cartão ou um certificado instalado no Windows**. É o mesmo
papel do PJeOffice: a chave do certificado nunca sai do seu computador, então a
assinatura acontece nele.

## Baixar

**[Baixar o Assinador do AdvBraz para Windows](https://github.com/JoseltonCalmon/advbraz-assinador/releases/latest/download/AssinadorAdvBraz.exe)**

Windows 10 ou 11. Não precisa instalar mais nada antes.

## Instalar

1. Dê dois cliques no `AssinadorAdvBraz.exe` que você baixou.
2. Se o Windows mostrar **"O Windows protegeu o computador"**, clique em
   **Mais informações** e depois em **Executar assim mesmo**. O aviso aparece porque o
   programa ainda não tem assinatura de código; ele não indica problema no arquivo.
3. Em alguns segundos aparece **"Pronto: o Assinador do AdvBraz está funcionando"**.

Não pede senha de administrador. Ele sobe sozinho sempre que o Windows inicia e
fica escondido, sem janela. Na primeira assinatura pelo site, o navegador pode
perguntar se o AdvBraz pode acessar este computador: permita.

## O que ele faz e o que não faz

- Só atende o AdvBraz: pedido de qualquer outro site é recusado.
- Não vê o seu PIN: quem pede o PIN é o próprio token ou o aplicativo do certificado,
  na janela deles.
- Não guarda nem envia documentos: recebe só o resumo de cada documento e devolve a
  assinatura.

## Atualizar

Baixe o arquivo de novo pelo link acima e dê dois cliques: a versão nova substitui
a antiga.

## Desinstalar

**Configurações do Windows → Aplicativos → Aplicativos instalados → Assinador do
AdvBraz → Desinstalar.**

## Certificado em nuvem

Quem usa certificado em nuvem não precisa deste programa quando o AdvBraz se conecta
direto ao provedor.

## Versões

- **1.1.0** — primeira versão instalável.
