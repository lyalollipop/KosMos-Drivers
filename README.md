# KosMos-Drivers
Aplicativo de manutenção geral em dispositivos de armazenamentos


KosMos - Ferramenta de Diagnóstico e Manutenção de Disco
O KosMos é uma solução completa desenvolvida para diagnóstico, manutenção e gerenciamento de dispositivos de armazenamento. Projetado para ser rápido, seguro e eficiente, ele simplifica tarefas complexas do Windows em uma interface intuitiva.

🚀 Funcionalidades
Verificação de Integridade: Realiza testes reais de leitura e gravação para determinar a velocidade e autenticidade do seu dispositivo de armazenamento.

Manutenção de Disco: Executa correções de sistema de arquivos (via chkdsk) para garantir que o seu drive esteja livre de erros e corrupções.

Gravador Simples: Interface simplificada para cópia rápida de arquivos, com barra de progresso e opção de ejetar o dispositivo com segurança ao finalizar.

Clonagem de Dispositivos: Permite replicar a estrutura de pastas e dados de um diretório para outro de forma automatizada.

Formatação Segura: Ferramenta dedicada para formatação rápida (format.com), com proteções de segurança integradas para evitar erros acidentais no disco do sistema.

🛠 Tecnologias Utilizadas
Linguagem: Python 3

Interface: CustomTkinter (Design moderno e modo escuro)

Processamento: Subprocess (Integração direta com o motor do Windows)

⚠️ Aviso de Segurança
Este aplicativo requer Privilégios de Administrador para funcionar corretamente, pois utiliza comandos de baixo nível do sistema (chkdsk e format) para realizar a manutenção e formatação de discos.

Nota: Ao executar o programa, o Windows poderá solicitar permissão para que o app faça alterações no seu computador. Isso é necessário para que ele tenha autoridade para interagir diretamente com os drivers de armazenamento.

📥 Como usar
Baixe o executável mais recente na aba Releases.

Execute o arquivo .exe (o ícone do KosMos aparecerá).

O Windows solicitará permissão de administrador. Clique em "Sim".

Escolha a funcionalidade desejada no menu principal e siga as instruções na tela.
