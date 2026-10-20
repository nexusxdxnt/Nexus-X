# Changelog

Todas as mudanças notáveis do Nexus X são documentadas neste arquivo.

## [4.0.2] - 2026-10-16

### Corrigido
- Foto e nome trocados em outro PC ou pelo Painel Admin agora aparecem sozinhos, sem precisar sair e entrar de novo na conta. O app confere ao abrir, ao voltar para a janela e a cada 5 minutos.

## [4.0.1] - 2026-10-16

### Corrigido
- Nexus Command: digitar o valor junto com o comando agora funciona. "volume 40" (ou "vol 40", "som 80") mostra "Definir volume para 40%" e o Enter aplica na hora.
- Manual do Nexus Command: o brilho avisa que só aparece em monitores que aceitam ajuste pelo Windows.

## [4.0.0] - 2026-10-16

Chegou o Nexus Command: aperte Alt + N em qualquer lugar do Windows e abra jogos, programas, arquivos e as ferramentas do Nexus digitando poucas letras.

### Novo
- Nexus Command (Alt + N): uma barra no visual de jogo que abre por cima de tudo. Busca jogos, programas, arquivos e pastas, e acha pela palavra do meio e com as palavras em qualquer ordem.
- Jogos da Steam, Epic Games e Riot com o ícone de cada um, além dos atalhos da área de trabalho. "Otimizar o PC e jogar" libera a memória e abre o jogo em seguida.
- Painel do item escolhido com as ações à mostra, e prévia de imagem, vídeo e música com play.
- Arraste arquivos da barra direto para o WhatsApp, o Discord ou uma pasta.
- Pesquisa rápida: yt para o YouTube, sp para o Spotify, endereços de sites, Google e calculadora.
- Controle do PC pela barra: volume, brilho, Wi-Fi, Bluetooth, seu IP, bloquear, desligar e reiniciar.
- Tudo que você copia fica guardado e dá para buscar e copiar de novo.
- Favoritos (Ctrl + D) e histórico do que você abriu.
- Botões embaixo: Otimizar (Alt + 1), Limpar histórico (Alt + 2) e Manual (Alt + 3), com tudo que a barra faz e exemplos para testar.
- A barra lembra onde você parou ao reabrir e se ajusta ao tamanho da tela, também em notebooks com o zoom do Windows em 125% ou 150%.
- Liga só com licença ativa. Dá para trocar o atalho nas Configurações.

## [3.1.1] - 2026-10-16

### Novo
- Atualizações e downloads agora vêm do site da DXN'T (nexusx.dxnt.com.br), com o GitHub como reserva. O app continua se atualizando sozinho mesmo se um dos dois sair do ar.
- Contrato de licença do instalador reescrito: planos, conta, pagamento pelo Asaas e o que o app altera no Windows.

## [3.1.0] - 2026-10-16

Entrada, compra e perfil refeitos: login com abas, uma tela de licença no formato de loja de jogo e um menu de perfil no lugar dos botões soltos.

### Novo
- Menu do perfil: clique no seu avatar no topo para abrir Configurações, Painel Admin (só para administradores) e Sair. Ele mostra também o nome do app, a versão e a DXN'T.
- Login com abas Entrar e Criar conta. O cadastro ganhou visual próprio em dourado, confirmação de senha e medidor de força; o login ganhou o botão para mostrar a senha.
- Tela de licença refeita no formato de loja de jogo, ocupando a janela inteira, com uma barra de compra fixa que mostra o plano, o preço e o botão.
- Pagamento mais claro: Pix ou cartão lado a lado, campos que se formatam sozinhos (CPF, cartão, validade e CEP) e o aviso de que a cobrança é feita pelo Asaas e o Nexus X não guarda os dados do cartão.
- Pix com QR Code grande, botão para copiar o código e passo a passo. O acesso libera sozinho quando o banco confirma, sem precisar mandar comprovante.
- Ativação por chave em tela própria.
- Primeiro acesso redesenhado, como a criação de um jogador.
- Telas de carregamento no formato do conteúdo nas Configurações e no Painel Admin, sem mostrar "0" enquanto os dados chegam.
- Painel Admin: aba Usuários para editar nome, foto, email e senha das contas e excluir contas, contadores mais compactos e listas que abrem na hora.

### Corrigido
- Tela vazia ao entrar com outra conta quando a anterior estava no Painel Admin.
- O plano Mensal agora explica que vale 30 dias e não renova sozinho.

### Por dentro
- Código reorganizado em pastas por área e estilos divididos por tela, um terço menores, sem mudar nada no visual.
- Removido um componente de início automático que não era usado (o início com o Windows continua funcionando igual).
- Contrato de licença do instalador agora em português.

## [3.0.0] - 2026-10-16

A maior atualização do Nexus X: visual novo inspirado em jogos, telas refeitas do zero e uma Verificação de Segurança que agora encontra e corrige problemas de verdade.

### Visual novo
- Lobby de jogo: menu no topo, no lugar da barra lateral, e tudo cabe na janela sem rolar a página.
- Tela Início nova, com o estado real do PC (RAM, lixo no disco e rede) e o botão "Otimizar agora", que roda memória, arquivos temporários e rede em sequência.
- Memória: RAM e disco lado a lado; o lixo do disco aparece como loot com raridade pelo tamanho.
- Rede: os cinco ajustes viraram uma trilha de fases que acende conforme roda.
- Modo Extremo: os ajustes viraram cartas para escolher, e os programas que abrem com o Windows viraram cartas para ligar e desligar.
- Configurações no formato de menu de opções de jogo, abrindo na hora (os dados são carregados uma vez ao abrir o app).
- Intro nova a cada abertura, e a janela só aparece quando ela já está pronta (sem tela vazia).
- Painel da bandeja no visual do app: clique com o botão direito no ícone perto do relógio para ver a RAM ao vivo e usar as ações rápidas.
- O resultado de cada ação aparece no próprio botão, sem avisos flutuantes.

### Segurança
- Varredura profunda agora faz mais que a rápida: passa o antivírus do Windows, procura arquivos suspeitos dos últimos 30 dias e lê de verdade o resultado do SFC e do DISM (antes sempre davam "inconclusivo").
- Botão para cancelar a varredura no meio.
- "Corrigir" confere de novo depois de aplicar e só some com o problema resolvido; antes anunciava sucesso mesmo quando o Windows recusava.
- A nota recalcula na hora ao corrigir, ignorar ou confiar, e a lista mostra só o que precisa de atenção.
- Tarefas agendadas suspeitas podem ser desativadas direto pelo app.

### Licenças
- Novos planos Anual (365 dias) e Teste grátis (3 dias, uma vez por conta, chave que várias pessoas podem usar).
- Painel de licenças redesenhado, com filtros, ações com nome e confirmação antes de excluir.
- Excluir licença funciona e todas as ações conferem se o banco aplicou a mudança.

### Corrigido
- Janela branca ao abrir o app pela bandeja depois de reiniciar o PC.
- Início automático com o Windows: o app não é mais fechado depois de 72 horas nem deixa de abrir no notebook fora da tomada.
- Alertas falsos de "Proteção em tempo real desligada" e "Proteção contra adulteração desligada" no Windows Defender.
- Programas legítimos assinados (como o Raycast) acusados como tarefa agendada suspeita.
- Clique esquerdo no ícone da bandeja agora traz o app para a frente mesmo quando ele está atrás de outras janelas.
- Removido o menu de clique direito do navegador embutido (Atualizar, Imprimir, Inspecionar) e os atalhos dele.

### Removido
- Módulo Otimizar Jogos.

## [2.5.0] - 2026-07-23

### Adicionado
- Otimização dedicada para VALORANT: perfis Máximo FPS/Competitivo/Balanceado, prioridade de processo, overlays desativados e ajuste do GameUserSettings.ini com backup e restauração — sem tocar em nada relacionado ao Riot Vanguard (Secure Boot, TPM, VBS/HVCI, serviços do anti-cheat).
- Otimização para mais 5 jogos: Minecraft Java Edition (memória e coletor de lixo da JVM, options.txt), Minecraft Bedrock Edition, EA Sports FC 26, GTA V (Legacy e Enhanced) e Roblox — cada um com o nível de automação compatível com o anti-cheat do próprio jogo.
- Busca por nome e filtro por categoria (FPS, MOBA, Sandbox, Esportes, Mundo Aberto) na tela de Otimizar Jogos.
- Dois novos ajustes no Modo Extremo: núcleos da CPU sempre ativos (sem estacionamento) e USB sempre ativo (sem suspensão seletiva).

### Corrigido
- Lista de otimizações do Modo Extremo agora rola só dentro do próprio quadro, sem rolar a página inteira.
- Animação de entrada dos cards de jogos: antes só o segundo card da grade animava; agora todos entram em cascata.

## [2.4.0] - 2026-07-06

### Adicionado
- Tela de carregamento nova a cada abertura do app: logo, barra de progresso e leitura dos módulos, com transição suave até a interface. Também aparece ao restaurar o app da bandeja.
- Troca de email e de senha direto em Configurações, no novo bloco "Conta e acesso". As duas ações exigem a senha atual, e a troca de email só conclui após confirmar pelo link enviado.

### Melhorado
- Tela inicial da Verificação de Segurança redesenhada: lista das 15 frentes verificadas e painel de varredura com radar animado.
- Lista de apps de inicialização agora entra com animação em cascata e rola apenas dentro do quadro, sem rolar a página.

### Corrigido
- Configurações abria com um "flash" de conteúdo vazio antes de carregar perfil e opções; agora exibe o estado de carregamento até os dados estarem prontos.

## [2.3.0] - 2026-07-06

### Adicionado
- Exclusão opcional da pasta do Nexus X no Windows Defender, para reduzir alertas causados pelas otimizações do app. Pede consentimento explícito na primeira execução e também pode ser ativada depois em Configurações; nunca mexe em nada fora da própria pasta do app nem desliga qualquer proteção do Windows.

### Corrigido
- Limpeza de cache: o espaço "recuperável" mostrado na tela agora reflete o que realmente será apagado. Antes, arquivos protegidos por terem sido usados recentemente entravam no total exibido mas não eram removidos, dando a impressão de que a limpeza não funcionava.

## [2.2.0] - 2026-07-05
- Módulo de Verificação de Segurança (Windows Defender, firewall, processos, persistência, acesso remoto, integridade do sistema e mais).
- RAM e cache de disco turbinados, com mais fontes de limpeza detalhadas.
- Nova lista de itens de inicialização do Windows.

## [2.1.0] - 2026-07-05
- Compra de licença direto pelo app via Asaas (Pix ou cartão).
- Atualização obrigatória antes de liberar o uso quando há nova versão.
- Correção: a licença só é criada depois que o pagamento é confirmado.

## [2.0.1] - 2026-07-04
- Instalador assinado como DXN'T.

## [2.0.0] - 2026-07-04
- Landing page nova.
- Faxina geral no código e otimização do build.

## [1.0.2] - 2026-07-04
- Correção na publicação cross-repo da release.

## [1.0.1] - 2026-07-04
- Auto-update, tela de onboarding, ajustes de bandeja e ícones.
