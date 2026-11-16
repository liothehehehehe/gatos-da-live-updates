# Gatos da Live

Distribuição oficial das versões beta do Gatos da Live para Windows 64 bits.

**[Baixar a versão atual — 3.4.0-beta.8](https://github.com/liothehehehehe/gatos-da-live-updates/releases/tag/v3.4.0-beta.8)** — escolha **Gatos-da-Live.zip**, o pacote completo do aplicativo, personagens, cenários e webcam. Os arquivos automáticos “Source code” do GitHub não são o instalador.

## Novidades da beta.8

- Golquadrado com caminhada em loop aprovada; a sprite de corrida antiga foi removida.
- Gol preto com motorista visível, entrada e saída animadas, visita e retorno de ré.
- Música a partir de 00:38, com som abafado dentro do carro, aproximação antes de aparecer, posição estéreo e fade ao se afastar.
- Banguela agora pode dizer não aos pedidos do chat com uma animação de recusa.
- É preciso ter quatro corações para votar em sossego, companhia ou brincar. Mesmo com afinidade suficiente, há 30% de chance de recusa; as formas09/10 sempre recusam brincar.
- Mantidos memória, reencontros, história do cantinho, evolução assistida por visitas, prêmio de afinidade e progresso no AppData.

**258 testes automatizados passaram**, além da validação do pacote assinado e do teste isolado de atualização, remoção da corrida antiga e persistência do progresso após trocar a pasta do programa.

Os GIFs de reação, emotes e vídeos avulsos de revisão ficam fora do aplicativo.

## Atualizar

Da **beta.2 em diante**, feche o OBS e use **Aplicativo → Atualizações → Verificar atualizações agora**, com a instalação automática habilitada. A assinatura é a mesma dessas versões.

Manual: extraia o ZIP completo em uma pasta separada e execute `ATUALIZAR-NESTE-PC.bat --destino "PASTA_DA_INSTALACAO_EXISTENTE"`, usando o caminho indicado por `root` em `http://127.0.0.1:4380/api/health`. Feche OBS e painel antes da atualização manual. O destino padrão do instalador é antigo; indique o destino explicitamente. Não copie os arquivos por cima nem apague os dados antes da migração.

Na primeira abertura da beta.7, mantenha o OBS fechado para atualizar o registro da integração nas cenas existentes. Confira no diagnóstico **version = 3.4.0-beta.8**, **root** da pasta do programa correto e **dataRoot** apontando para o AppData. Confirme o progresso no painel antes de remover a pasta anterior.

Após migrar, outra pasta de versão compatível pode reabrir o mesmo perfil, mesmo se a pasta anterior for removida. O aplicativo ainda precisa dos arquivos do programa e das artes. Versões antigas, sem suporte ao AppData, não devem ser usadas para continuar o mesmo save. Bases divergentes ou corrompidas são bloqueadas, sem mesclar recibos ou criar um gato novo. Os backups são locais; mudar de usuário do Windows ou computador pode exigir reconectar as contas.

Quem ainda usa a **beta.1** precisa atualizar manualmente porque a chave de assinatura antiga ficou indisponível.

## Fontes no OBS

Com o aplicativo atualizado em execução:

| Fonte | Endereço local | Tamanho da arte |
| --- | --- | --- |
| Webcam | `http://127.0.0.1:4380/webcam/overlay.html` | 1344 × 914 |
| Conversa moderna | `http://127.0.0.1:4380/conversa-moderna/overlay.html` | 1920 × 1080 |
| Encerrando animado | `http://127.0.0.1:4380/montanhas-animadas/overlay.html` | 1920 × 1080 |
| Live iniciando | `http://127.0.0.1:4380/inicio-live/index.html` | 1920 × 1080 |

As fontes manuais são preservadas. Na base OBS 2560 × 1440, mantenha a escala proporcional das artes. Não adicione outro personagem do gato ao encerramento; ele já está no ombro do streamer. A fonte antiga do painel offline fica transparente.

[Baixar LIVE OFFLINE em PNG](https://github.com/liothehehehehe/gatos-da-live-updates/releases/download/v3.4.0-beta.8/LIVE-OFFLINE.png). O vídeo de encerramento está em `public/montanhas-animadas/Encerrando-Montanhas.mp4`.

Chat para copiar no editor: `public/chat-streamelements/`, `public/chat-streamelements-10s/` e `public/chat-camera-largo/`. A variante conversa usa widget 523 × 871 em X112,Y371 na base 2560 × 1440. O chat de câmera acompanha sua largura efetiva no OBS; a aproximação usada no teste foi 830 × 420. O aplicativo não modifica o widget na conta StreamElements.

Os últimos follower/sub dependem da conta StreamElements conectada. Páginas de prévia e `TESTAR-CENAS.bat` usam exemplos e simulação sem compras, pontos ou progresso real.

## Verificação

258 testes automatizados aprovados. Pacote assinado Ed25519, SHA256 e manifesto. Ensaio isolado de instalação, migração ao AppData, aplicação única dos ajustes e reabertura do mesmo perfil depois de remover a instalação anterior. A publicação confere os arquivos remotos e a assinatura disponibilizada.

Nenhuma instalação real do streamer foi modificada durante a publicação. Saves, credenciais e chaves privadas não são distribuídos; os testes usam dados e integrações simulados.
