# Sala dos agentes

Painel local que mostra, ao vivo, as sessões do Claude Code de um workspace e os agentes que elas disparam, ao lado de um quadro com as suas tasks. Tudo roda na sua máquina.

## Baixar

**[Baixar a versão mais recente (Windows 10 e 11, 64 bits)](https://github.com/marcotancredo/sala-agentes-app/releases/latest/download/sala-agentes-win-x64.zip)**

As versões anteriores ficam em [Releases](https://github.com/marcotancredo/sala-agentes-app/releases).

## Como usar

1. Extraia o zip e coloque o `sala-agentes.exe` numa pasta sua, por exemplo `C:\Ferramentas\Sala dos agentes`.
2. Dê dois cliques nele. A sala abre numa janela própria e o servidor fica em segundo plano.
3. Na primeira vez, escolha o workspace (a pasta do projeto) e, se quiser, aceite criar o atalho.

Não precisa instalar o Node: ele já vai dentro do executável. Para as conversas pela sala, o Claude Code precisa estar instalado e com login feito.

## Aviso do Windows

O executável não é assinado. Na primeira vez, o Windows pode mostrar "O Windows protegeu o computador": clique em "Mais informações" e depois em "Executar assim mesmo".

## Atualizar

Troque o `sala-agentes.exe` pelo novo e abra de novo. Se a sala antiga estiver aberta, a nova assume o lugar dela.

## Onde ficam os dados

Configurações, log e preferências ficam em `%USERPROFILE%\.claude\sala-agentes`. Para desinstalar, apague o executável, os atalhos "Sala dos agentes" e essa pasta.
