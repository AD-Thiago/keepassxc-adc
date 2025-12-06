# <img src="https://keepassxc.org/assets/img/keepassxc.svg" width="40" height="40"/> KeePassXC
[![OpenSSF Best Practices](https://bestpractices.coreinfrastructure.org/projects/6326/badge)](https://bestpractices.coreinfrastructure.org/projects/6326)
[![TeamCity Build Status](https://ci.keepassxc.org/app/rest/builds/buildType:\(project:KeepassXC\)/statusIcon)](https://ci.keepassxc.org/?guest=1)
[![codecov](https://codecov.io/gh/keepassxreboot/keepassxc/branch/develop/graph/badge.svg)](https://codecov.io/gh/keepassxreboot/keepassxc)
[![GitHub release](https://img.shields.io/github/release/keepassxreboot/keepassxc)](https://github.com/keepassxreboot/keepassxc/releases/)

[![Matrix community channel](https://img.shields.io/matrix/keepassxc:matrix.org?label=Community%20channel)](https://app.element.io/#/room/#keepassxc:mozilla.org)
[![Matrix development channel](https://img.shields.io/matrix/keepassxc-dev:matrix.org?label=Development%20channel)](https://app.element.io/#/room/#keepassxc-dev:mozilla.org)

[KeePassXC](https://keepassxc.org) é um gerenciador de senhas moderno, seguro e de código aberto que armazena e gerencia suas informações mais confidenciais. Você pode executar o KeePassXC em sistemas Windows, macOS e Linux. O KeePassXC é destinado a pessoas com exigências extremamente altas em relação ao gerenciamento seguro de dados pessoais. Ele salva muitos tipos diferentes de informações, como nomes de usuário, senhas, URLs, anexos e notas em um arquivo offline criptografado que pode ser armazenado em qualquer local, incluindo soluções de nuvem privada e pública. Para facilitar a identificação e o gerenciamento, títulos e ícones definidos pelo usuário podem ser especificados para as entradas. Além disso, as entradas são classificadas em grupos personalizáveis. Uma função de pesquisa integrada permite que você use padrões avançados para encontrar facilmente qualquer entrada em seu banco de dados. Um utilitário gerador de senhas personalizável, rápido e fácil de usar permite que você crie senhas com qualquer combinação de caracteres ou frases de senha fáceis de lembrar.




## Quick Start
O [Guia de Início Rápido](https://keepassxc.org/docs/KeePassXC_GettingStarted.html) ajuda você a começar a usar o KeePassXC no seu computador Windows, macOS ou Linux usando binários pré-compilados da [página de downloads](https://keepassxc.org/download). Além disso, distribuições Linux individuais podem fornecer suas próprias versões, portanto, verifique a lista de pacotes da sua distribuição para ver se o KeePassXC está disponível. A documentação detalhada está disponível no [Guia do Usuário](https://keepassxc.org/docs/KeePassXC_UserGuide.html).




## Lista de recursos
O KeePassXC possui vários recursos para usuários iniciantes e avançados. Nosso objetivo é criar um aplicativo que possa ser usado por qualquer pessoa, ao mesmo tempo em que oferece recursos avançados para aqueles que precisam deles.


### Básico
* Crie, abra e salve bancos de dados no formato KDBX (compatível com KeePass com KDBX4 e KDBX3)
* Armazene informações confidenciais em entradas organizadas por grupos
* Pesquise entradas
* Gerador de senhas
* Digite senhas automaticamente em aplicativos
* Integração com navegadores Google Chrome, Mozilla Firefox, Microsoft Edge, Chromium, Vivaldi, Brave e Tor-Browser
* Suporte para chaves de acesso usando a integração com navegadores
* Download de ícones de entradas
* Importe bancos de dados dos formatos CSV, 1Password, Bitwarden, Proton Pass e KeePass1


### Avançado
* Relatórios do banco de dados (integridade da senha, HIBP e estatísticas)
* Exportação do banco de dados para os formatos CSV, XML e HTML
* Armazenamento e geração de TOTP
* Referências de campo entre entradas
* Anexos de arquivos e atributos personalizados
* Histórico de entradas e restauração de dados
* Suporte a desafio-resposta YubiKey/OnlyKey
* Interface de linha de comando (keepassxc-cli)
* Abertura automática de bancos de dados
* Bancos de dados compartilhados KeeShare (importação, exportação e sincronização)
* Integração com SSH Agent
* FreeDesktop.org Secret Service (substitui o Gnome keyring, etc.)
* Opções adicionais de criptografia: Twofish e ChaCha20


For a full list of changes, read the [CHANGELOG](CHANGELOG.md) document. \
For a full list of keyboard shortcuts, see [KeyboardShortcuts.adoc](./docs/topics/KeyboardShortcuts.adoc)

## Building KeePassXC

Instruções detalhadas estão disponíveis na página [Compilar e instalar](./INSTALL.md) e na [Wiki](https://github.com/keepassxreboot/keepassxc/wiki/Building-KeePassXC).
## Contribuições
Estamos sempre buscando sugestões sobre como melhorar o KeePassXC. Se você encontrar algum bug ou tiver uma ideia para um novo recurso, informe-nos abrindo um relatório no [rastreador de problemas](https://github.com/keepassxreboot/keepassxc/issues) no GitHub ou junte-se a nós no [canal da comunidade Matrix](https://matrix.to/#/! zUxwGnFkUyycpxeHeM:matrix.org?via=matrix.org) ou [canal de desenvolvimento Matrix](https://matrix.to/#/! RhJPJPGwQIFVQeXqZa:matrix.org?via=matrix.org) ou no IRC nos canais #keepassxc e #keepassxc-dev do [Libera.Chat](https://web.libera.chat/).
Você pode contribuir diretamente com seu próprio código enviando uma solicitação pull. Leia o documento [CONTRIBUIÇÃO](.github/CONTRIBUTING.md) para obter mais informações.
Os colaboradores devem aderir ao [Código de Conduta](CODE-OF-CONDUCT.md) do projeto.



## Generative AI

A IA generativa está se tornando rapidamente um recurso próprio na maioria dos ambientes de desenvolvimento, incluindo o próprio GitHub. Se a maior parte de um envio de código for feita usando IA generativa (por exemplo, codificação baseada em agente ou vibe), **documentaremos isso na solicitação de pull.** Todos os envios de código passam por um rigoroso processo de revisão, independentemente do fluxo de trabalho de desenvolvimento ou do remetente.




## Licença
O código do KeePassXC está licenciado sob a GPL-2 ou GPL-3. O licenciamento adicional para arquivos de terceiros está detalhado em [COPYING](./COPYING).
