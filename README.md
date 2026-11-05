# Gatos da Live

Distribuição oficial das versões de teste do Gatos da Live para Windows 64 bits.

**[Baixar a versão atual — 3.4.0-beta.3](https://github.com/liothehehehehe/gatos-da-live-updates/releases/tag/v3.4.0-beta.3)** — em Assets, escolha `Gatos-da-Live.zip` para o projeto completo.

**[Webcam nova em pacote separado](https://github.com/liothehehehehe/gatos-da-live-updates/releases/download/v3.4.0-beta.3/Webcam-R0muloss-Final-2026-11-05.zip)** — arte, máscara, fonte e demonstração. Os nomes ao vivo dependem do aplicativo atualizado em execução.

## Novidades da beta.3

- Michel exclusivo de `m1chelziiin`, com carro HD, rodas e porta animadas, caminhada contínua, comida/carinho, retorno ao carro e saída de ré. Escala e apoio no chão ajustados. Música original aumenta com a aproximação e diminui somente depois que o carro sai completamente da tela.
- Sub padrão corrigido para assinantes que também são VIPs ou moderadores. Personagens exclusivos continuam prioritários.
- BOTBanguela com reconexão revisada, ponte reserva StreamElements e troca automática ou guiada. Streamer/moderadores podem usar `!bot auto`, `!bot banguela`, `!bot streamelements` e `!bot status`.
- Webcam com painel expansível, centralização do Banguela ao recolher, piscadas e expressão brava, últimos follower/sub e luz lavanda nos contornos. YouTube `@r0omuloss`; demais redes `@r0muloss`.
- Tela LIVE INICIANDO com vale em camadas, chuva, raios, grama animada e Banguela no ombro do personagem.

Os remakes, a cozinha e os ciclos aprovados do Banguela da beta.2 permanecem incluídos. As transições são estudos para revisão futura e não foram ativadas nas cenas.

## Fontes novas no OBS

Com o aplicativo atualizado em execução:

- Webcam: `http://127.0.0.1:4380/webcam/overlay.html` — Fonte de navegador, 1344 × 914.
- Início: `http://127.0.0.1:4380/inicio-live/index.html` — Fonte de navegador, 1920 × 1080.

As fontes manuais existentes não são substituídas. Os últimos nomes são lidos da sessão StreamElements conectada e preservados em cache. A integração foi testada com respostas simuladas; a conta real e o diagnóstico da desconexão histórica dependem da conferência na instalação da live.

`TESTAR-CENAS.bat` abre um laboratório local de cenas e visitas. A simulação não gasta pontos nem altera o progresso real.

## Atualizar

Da **beta.2**, a beta.3 usa a mesma chave de assinatura e pode ser instalada em **Aplicativo → Atualizações**, com OBS fechado e sem recibos pendentes.

Para atualização manual:

1. Fora da transmissão e da gravação, feche o OBS e saia do painel antigo pela bandeja.
2. Extraia o ZIP completo em uma pasta separada da instalação.
3. Execute `ATUALIZAR-NESTE-PC.bat` e indique sua instalação existente.
4. O atualizador faz backup e preserva progresso, afinidades, recibos, credenciais, configurações e fontes manuais do OBS.

Quem ainda usa a **beta.1** precisa dessa migração manual: a chave antiga ficou indisponível e não valida os pacotes novos. Não apague o save nem sobreponha arquivos manualmente.

## Instalação nova

Extraia o ZIP completo em uma pasta fixa e abra `Gatos-da-Live-Painel.exe`. A primeira inicialização começa no Banguela **forma 2**, com zero horas de live. Conecte as contas e confira as cenas existentes pelo nome.

## Verificação

Beta.3: 178 testes passaram; 998 arquivos conferidos. Pacote assinado com Ed25519, SHA256 e manifesto. Instalação isolada validada com preservação de dados. Nenhuma compra ou mensagem real foi feita na validação.

Arquivos obsoletos só são removidos quando pertenciam ao manifesto anterior e continuam com seu conteúdo original; arquivos modificados manualmente são preservados. São mantidos os dois backups de atualização validados mais recentes.

Credenciais, chaves privadas e saves não são distribuídos. As versões deste canal são **beta**.
