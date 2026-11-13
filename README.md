# LK Launcher — distribuição oficial

Instaladores e atualizações do LK Launcher. Este repositório contém somente
instruções e arquivos de distribuição; os fontes de desenvolvimento e as chaves
privadas permanecem fora dele.

## Instalar

Baixe o [instalador LK Launcher 1.0.1](https://github.com/luquez/olimpia-launcher-releases/releases/download/lk-v1.0.1/LichKing-Launcher-Setup-1.0.1.exe)
para Windows 10/11 de 64 bits e execute. Python e Node já estão incluídos.

Quem recebeu a Preview 0.8 precisa instalar a versão atual uma vez. Ela corrige a falha
`[Errno 2] No such file or directory` ao iniciar a atualização do BlackTalon.

## Atualizações do launcher

A partir da 1.0.0, o launcher consulta Releases `lk-v*` ao abrir. Uma versão nova
é baixada, tem sua assinatura e arquivos verificados e é aplicada quando não há
operação ou sessão de bot ativa. Se a validação de inicialização falhar, o
atualizador restaura a versão anterior. Há também o botão **Verificar launcher**.

A indisponibilidade do GitHub não bloqueia a versão já instalada. Contas,
preferências, perfis e jogos ficam fora da pasta substituída pelo atualizador.

## BlackTalon

Na aba BlackTalon, **Atualizar BlackTalon** baixa os arquivos oficiais e faz o
decrypt. Depois, com o jogo fechado, **Instalar vBot BlackTalon** prepara o bot.
**Atualizar e jogar** mantém o jogo atualizado e abre o client diretamente.

A versão 1.0.1 corrige janelas do vBot salvas fora da tela e preserva o log do
jogo sem bloquear atualizações. Depois de atualizar o launcher, use **Instalar
vBot BlackTalon** com o jogo fechado para aplicar o pacote corrigido ao jogo já
instalado. **Ctrl+Shift+U** abre o bot. O novo botão **Instalar terminal** adiciona
o terminal Lua, acessível por **Ctrl+T**. Modificações locais no bot são
preservadas e reportadas; o launcher não as substitui silenciosamente.
A compatibilidade de outros clients continua dependendo de seus adaptadores.

## Canal legado do Olimpia

As Releases `v1.*` continuam destinadas ao launcher antigo do Olimpia. O canal
`lk-v*` é separado e não substitui automaticamente o launcher antigo.
[Última distribuição legada](https://github.com/luquez/olimpia-launcher-releases/releases/latest).
