# Gatos da Live

Distribuição oficial das versões de teste do Gatos da Live para Windows 64 bits.

**[Baixar a versão atual](https://github.com/liothehehehehe/gatos-da-live-updates/releases/tag/v3.4.0-beta.1)** — em Assets, escolha `Gatos-da-Live.zip`.

## Instalação nova

1. Extraia o ZIP completo em uma pasta fixa.
2. Abra `Gatos-da-Live-Painel.exe`. Esta entrega começa no Banguela **forma 2**, com zero horas de live.
3. Conecte as contas e confira as cenas existentes pelo nome.

Se a pasta anterior foi apagada, esta é a instalação indicada; o pacote é completo. Para preparar a forma 2 em uma instalação ainda no bebê, feche OBS/painel e use `INICIAR-FORMA-2.bat`.

## Atualizar uma instalação que já existe

Extraia o pacote em uma pasta separada e execute `ATUALIZAR-NESTE-PC.bat`, com OBS e painel fechados. Progresso, afinidades, recibos e configurações são preservados.

A partir desta geração, **Aplicativo → Atualizações** consulta este repositório automaticamente. As próximas versões assinadas são baixadas em segundo plano e instaladas quando o OBS estiver fechado e não houver recibos pendentes. O aplicativo e o serviço reiniciam após a validação.

## Integridade e limpeza

Os pacotes automáticos são verificados por assinatura Ed25519, SHA256 e manifesto. A instalação preserva os dados locais. Arquivos obsoletos só são removidos quando pertenciam ao manifesto anterior e continuam com seu conteúdo original; arquivos modificados manualmente são preservados. São mantidos os dois backups de atualização validados mais recentes.

Credenciais e saves não são distribuídos neste repositório. A conta BOTBanguela responde ao chat; os pontos permanecem no StreamElements.

As versões deste canal são **beta**; o aplicativo consulta a lista de Releases, incluindo as versões beta assinadas.
