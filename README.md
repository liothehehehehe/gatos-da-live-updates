# Gatos da Live

Distribuição oficial das versões beta do Gatos da Live para Windows 64 bits.

**[Baixar a versão atual — 3.4.0-beta.4](https://github.com/liothehehehehe/gatos-da-live-updates/releases/tag/v3.4.0-beta.4)** — escolha `Gatos-da-Live.zip`. O pacote completo já inclui a webcam.

**[Baixar LIVE OFFLINE em PNG](https://github.com/liothehehehehe/gatos-da-live-updates/releases/download/v3.4.0-beta.4/LIVE-OFFLINE.png)** — imagem estática em 1920 × 1080.

## Novidades da beta.4

- Conversa moderna aprovada: título CONVERSA, fundo animado entre tons de roxo, câmera arredondada com sombra suave e redes centralizadas com ícones e fade. Sem luz percorrendo a câmera nem bloco duplicado de redes. Rotas, saltos, limites e comportamento dos gatos permanecem iguais.
- Encerramento com o streamer sentado nas montanhas e Banguela no ombro, raios nas nuvens, folhas ao vento e piscadas. ENCERRANDO alterna os cantos superior esquerdo/inferior direito no mesmo ritmo da tela de início.
- Removido o gato separado na cena offline/encerrando. As antigas fontes `source.html?panel=offline` e `render.html?panel=offline` ficam transparentes. Banguela permanece apenas na arte do ombro; não há visitas nessa cena.
- Versão estática da mesma paisagem com LIVE OFFLINE no canto superior esquerdo.
- Webcam completa dentro do projeto: painel expansível, centralização do Banguela, expressões, últimos follower/sub e contornos lavanda. YouTube `@r0omuloss`; demais redes `@r0muloss`.

Mantidos Michel (`m1chelziiin`) com carro HD/música/visita/ré, sub padrão corrigido para assinantes VIP/moderadores, reconexão e troca dos bots, remakes/ciclos/cozinha do Banguela e tela LIVE INICIANDO. Comandos de ponte: `!bot auto`, `!bot banguela`, `!bot streamelements`, `!bot status`, para streamer/moderadores. As transições experimentais continuam fora desta atualização.

## Fontes no OBS

Com o aplicativo atualizado em execução:

| Fonte | Endereço local | Tamanho |
| --- | --- | --- |
| Webcam | `http://127.0.0.1:4380/webcam/overlay.html` | 1344 × 914 |
| Conversa moderna | `http://127.0.0.1:4380/conversa-moderna/overlay.html` | 1920 × 1080 |
| Encerrando animado | `http://127.0.0.1:4380/montanhas-animadas/overlay.html` | 1920 × 1080 |
| Live iniciando | `http://127.0.0.1:4380/inicio-live/index.html` | 1920 × 1080 |

A atualização preserva as fontes manuais existentes. Para adotar as novas artes, substitua o fundo antigo da conversa/encerramento pelos endereços acima. Na conversa, câmera abaixo da moldura e chat/gatos acima: câmera X600,Y208,1232 × 693; área útil do chat X88,Y290,384 × 630. Máscara em `public/conversa-moderna/mascara-camera.png`.

Não adicione outro personagem do gato ao encerramento. A fonte antiga do painel offline agora fica transparente. A versão em vídeo está em `public/montanhas-animadas/Encerrando-Montanhas.mp4` (Fonte de mídia, Repetir). A imagem estática está em `public/montanhas-animadas/live-offline.png` (Fonte de imagem).

Os últimos nomes dependem da conta StreamElements conectada. As páginas de prévia usam exemplos. `TESTAR-CENAS.bat` permite simulação local sem compras, pontos ou progresso real.

## Atualizar

Da **beta.2 ou beta.3**, mantenha a instalação existente, feche o OBS e use **Aplicativo → Atualizações**. Marque **Baixar e instalar atualizações automaticamente** e clique **Verificar atualizações agora**. A beta.4 usa a mesma chave de assinatura.

Manual: extraia o ZIP completo em uma pasta separada e execute `ATUALIZAR-NESTE-PC.bat --destino "PASTA_DA_INSTALACAO_EXISTENTE"`, usando a pasta indicada em `root` no endereço local `/api/health`. O destino padrão do instalador é antigo; indique o destino explicitamente. Feche o OBS e o painel antigo antes da instalação manual.

Quem ainda usa a **beta.1** precisa migrar manualmente porque a chave antiga ficou indisponível. Não apague os dados nem sobreponha arquivos manualmente. O atualizador faz backup e preserva progresso, afinidades, recibos, contas, configurações e fontes manuais do OBS.

Instalação nova: extraia o ZIP completo em pasta fixa e abra `Gatos-da-Live-Painel.exe`; inicia na forma 2, sem inventar horas de live.

## Verificação

180 testes passaram; 1015 arquivos conferidos. Pacote assinado com Ed25519, SHA256 e manifesto. Atualização isolada validada com preservação de dados; os arquivos remotos e a assinatura publicada foram conferidos. Nenhuma instalação real do streamer foi alterada na preparação.

Credenciais, chaves privadas e saves não são distribuídos. Os testes de integrações usam respostas simuladas; a conta real e a causa da desconexão histórica do bot ainda dependem da conferência na instalação da live.
