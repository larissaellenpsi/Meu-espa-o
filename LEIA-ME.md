# Meu Espaço — aplicativo web instalável

Este pacote contém uma primeira versão independente do **Meu Espaço**, um organizador pessoal/profissional que funciona no navegador e pode ser instalado na tela inicial do celular.

## O que já está incluído
- Painel inicial e frase motivacional diária
- Agenda semanal e caixa de entrada de tarefas
- Áreas separadas para clínica de convênio e clínica particular
- Controles financeiros separados
- Banco de ideias de conteúdo
- Lista de burocracias e documentação
- Espaço pessoal e despejo mental
- Salvamento local no navegador (localStorage)
- Estrutura PWA e funcionamento offline após o primeiro acesso

## Importante sobre privacidade
Os dados ficam armazenados localmente no navegador/dispositivo. Não há conta, sincronização em nuvem, criptografia própria ou backup automático. Não registre nomes, diagnósticos, relatos, prontuários ou quaisquer dados identificáveis de pacientes. Use o app somente para organização administrativa genérica. Faça backup/exportação manual por meios seguros antes de trocar de aparelho ou limpar os dados do navegador.

## Como colocar no ar gratuitamente com GitHub Pages
1. Entre em https://github.com e crie uma conta, se ainda não tiver.
2. Crie um repositório novo chamado `meu-espaco`.
3. Envie os arquivos deste pacote para a raiz do repositório: `index.html`, `manifest.webmanifest`, `sw.js` e `icon.svg`.
4. No repositório, abra **Settings → Pages**.
5. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e `/ (root)`, e salve.
6. Aguarde a publicação. O GitHub mostrará um endereço HTTPS parecido com `https://seu-usuario.github.io/meu-espaco/`.

## Como instalar no iPhone
1. Abra o endereço HTTPS no Safari.
2. Toque em **Compartilhar**.
3. Escolha **Adicionar à Tela de Início**.
4. Confirme em **Adicionar**.

## Como instalar no Android
1. Abra o endereço HTTPS no Chrome.
2. Abra o menu de três pontos.
3. Escolha **Instalar app** ou **Adicionar à tela inicial**.

## Limitações desta versão
- Não sincroniza entre dispositivos.
- Não envia notificações nem lembretes push.
- Não se conecta ao Google Calendar.
- Os lançamentos financeiros são controles manuais, não integração bancária.
- A publicação no GitHub Pages precisa ser feita pela titular da conta; este pacote não foi publicado na internet.
