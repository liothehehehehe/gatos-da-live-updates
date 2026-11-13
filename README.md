# Gatos da Live

Distribuição oficial das versões beta do Gatos da Live para Windows 64 bits.

**[Baixar a versão atual — 3.4.0-beta.6](https://github.com/liothehehehehe/gatos-da-live-updates/releases/tag/v3.4.0-beta.6)** — escolha **Gatos-da-Live.zip**, o pacote completo do aplicativo, personagens, cenários e webcam. Os arquivos automáticos “Source code” do GitHub não são o instalador.

## Novidades da beta.6

- Remakes das cinco formas gordas do Banguela (06–10), integrados ao aplicativo e à cozinha, com ciclos próprios e cuidados.
- Formas 09/10 com caminhada lenta, barriga para cima, alimentação e sono; corrida e saltos para plataformas bloqueados. Tentativa de pulo com esforço e um saltinho mínimo, retornando ao mesmo lugar.
- As duas formas finais ficam numa faixa do chão da cozinha; posições antigas em plataformas são corrigidas.
- Contorno roxo padronizado na exibição; barriga da forma 10 aproximada da 09; membros extras corrigidos, incluindo higiene da forma 10, quadro 6.
- Dash aprovado do adulto normal, Thor e dragões preservados.

## Mantido da beta.5

- Personagem exclusivo de **skaveox**, com movimento contínuo e ações de carinho, comida, ajoelhar, levantar, acenar e gestos. O vínculo usa o login nativo `skaveox`.
- Base persistente fora da pasta da versão: `%LOCALAPPDATA%\Gatos-da-Live\Perfis\r0muloss\perfil`. Progresso, afinidades, recibos, fila de comandos, credenciais e configurações pessoais são migrados com conferência e backup externo, preservando os originais.
- Integração Lua do OBS em caminho estável e diagnóstico com `dataRoot`.
- Ajuste único solicitado: Thainá (`darlingthai`) com 2 corações e 95% rumo ao terceiro; Alan (`alanrodsy`) com 3; Rômulo (`r0muloss`) com 1 e 95% rumo ao segundo; skaveox com 1. Progresso que já estiver acima é preservado.
- Banguela na forma/nível 2, com 70% do intervalo até a forma 3 concluído e 30% restante. Mantém alimentação, dívida e horas de live; não regride um gato mais avançado. O ajuste é registrado no save para não se repetir. Pendências financeiras adiam sua aplicação até uma abertura segura após conferência.
- Arquivos dos widgets de chat StreamElements nas versões permanente, 10 segundos e largura ajustável. Incluem os distintivos originais recebidos pelo serviço. A instalação do widget no editor do StreamElements continua manual.

**Os GIFs de reação e memes criados separadamente não estão neste pacote.**

Mantidos os remakes/ciclos e cozinha do Banguela, Michel (`m1chelziiin`) com carro HD, música e saída de ré, sub padrão, reconexão e troca dos bots, webcam, conversa moderna, LIVE INICIANDO, ENCERRANDO e LIVE OFFLINE. Comandos de ponte para streamer/moderadores: `!bot auto`, `!bot banguela`, `!bot streamelements`, `!bot status`.

## Atualizar

Da **beta.2, beta.3, beta.4 ou beta.5**, feche o OBS e use **Aplicativo → Atualizações → Verificar atualizações agora**, com a instalação automática habilitada. A assinatura é a mesma dessas versões.

Manual: extraia o ZIP completo em uma pasta separada e execute `ATUALIZAR-NESTE-PC.bat --destino "PASTA_DA_INSTALACAO_EXISTENTE"`, usando o caminho indicado por `root` em `http://127.0.0.1:4380/api/health`. Feche OBS e painel antes da atualização manual. O destino padrão do instalador é antigo; indique o destino explicitamente. Não copie os arquivos por cima nem apague os dados antes da migração.

Na primeira abertura da beta.6, mantenha o OBS fechado para atualizar o registro da integração nas cenas existentes. Confira no diagnóstico **version = 3.4.0-beta.6**, **root** da pasta do programa correto e **dataRoot** apontando para o AppData. Confirme o progresso no painel antes de remover a pasta anterior.

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

[Baixar LIVE OFFLINE em PNG](https://github.com/liothehehehehe/gatos-da-live-updates/releases/download/v3.4.0-beta.6/LIVE-OFFLINE.png). O vídeo de encerramento está em `public/montanhas-animadas/Encerrando-Montanhas.mp4`.

Chat para copiar no editor: `public/chat-streamelements/`, `public/chat-streamelements-10s/` e `public/chat-camera-largo/`. A variante conversa usa widget 523 × 871 em X112,Y371 na base 2560 × 1440. O chat de câmera acompanha sua largura efetiva no OBS; a aproximação usada no teste foi 830 × 420. O aplicativo não modifica o widget na conta StreamElements.

Os últimos follower/sub dependem da conta StreamElements conectada. Páginas de prévia e `TESTAR-CENAS.bat` usam exemplos e simulação sem compras, pontos ou progresso real.

## Verificação

207 testes automatizados aprovados. Pacote assinado Ed25519, SHA256 e manifesto. Ensaio isolado de instalação, migração ao AppData, aplicação única dos ajustes e reabertura do mesmo perfil depois de remover a instalação anterior. A publicação confere os arquivos remotos e a assinatura disponibilizada.

Nenhuma instalação real do streamer foi modificada durante a publicação. Saves, credenciais e chaves privadas não são distribuídos; os testes usam dados e integrações simulados.
