# Gatos da Live

Distribuição oficial das versões de teste do Gatos da Live para Windows 64 bits.

**[Baixar a versão atual — 3.4.0-beta.2](https://github.com/liothehehehehe/gatos-da-live-updates/releases/tag/v3.4.0-beta.2)** — em Assets, escolha `Gatos-da-Live.zip`.

## Novidades desta versão

Banguela remake na cozinha, movimentos revisados das formas 2 a 5, caminhar novo da forma 3 e adulto com suas ações. Os dashes aprovados foram preservados. Novo VIP padrão para subs sem personagem exclusivo e Golquadrado, vinculado a `golquadradooriginal`, com corrida contínua e ações de comida, carinho e gestos.

`TESTAR-CENAS.bat` abre um laboratório local com seis cenas, escolha de forma e visitas manuais ou automáticas. A simulação não gasta pontos nem altera o progresso real; visitas continuam disponíveis apenas nas cenas permitidas.

## Atualização manual necessária da beta.1 para a beta.2

A chave de assinatura ficou indisponível no computador anterior. Esta versão usa uma nova chave: a beta.1 não consegue validar essa assinatura pelo atualizador automático.

1. Fora da transmissão e da gravação, feche o OBS e saia do painel antigo pela bandeja.
2. Baixe e extraia o ZIP completo em uma pasta separada da instalação.
3. Execute `ATUALIZAR-NESTE-PC.bat` e indique a instalação existente.
4. O atualizador faz backup e preserva progresso, afinidades, recibos, credenciais, configurações e fontes manuais do OBS.

Não apague o save nem sobreponha os arquivos manualmente. Após esta atualização manual, o aplicativo passa a confiar na nova chave para as próximas versões automáticas.

## Instalação nova

Extraia o ZIP completo em uma pasta fixa e abra `Gatos-da-Live-Painel.exe`. A primeira inicialização começa no Banguela **forma 2**, com zero horas de live. Conecte as contas e confira as cenas existentes pelo nome.

## Integridade e limpeza

O pacote é verificado por assinatura Ed25519, SHA256 e manifesto. Arquivos obsoletos só são removidos quando pertenciam ao manifesto anterior e continuam com seu conteúdo original; arquivos modificados manualmente são preservados. São mantidos os dois backups de atualização validados mais recentes.

Credenciais, chaves privadas e saves não são distribuídos neste repositório. A conta BOTBanguela responde ao chat; os pontos permanecem no StreamElements.

As versões deste canal são **beta**. As próximas versões assinadas pela nova chave podem ser consultadas e instaladas em **Aplicativo → Atualizações**, com OBS fechado e sem recibos pendentes.
