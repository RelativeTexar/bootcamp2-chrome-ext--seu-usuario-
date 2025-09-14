Bootcamp Helper — Extensão para Chrome
Uma extensão de exemplo criada para a Etapa Inicial do Bootcamp II, com o objetivo de praticar o desenvolvimento de extensões para Google Chrome utilizando o Manifest V3.

🚀 Funcionalidades
Popup Interativo: Uma interface simples que se comunica com o Service Worker da extensão.

Comunicação Bidirecional: O popup envia mensagens para o Service Worker, que responde com informações em tempo real.

Ação em Segundo Plano: Um Service Worker que roda em background, gerenciando eventos da extensão e a lógica de comunicação.

🛠️ Estrutura do Projeto
A arquitetura do projeto segue a estrutura de pastas recomendada para o Manifest V3, garantindo organização e modularidade.

my-chrome-extension/
├─ src/
│  ├─ popup/
│  │  ├─ popup.html
│  │  ├── popup.js
│  │  └─ popup.css
│  ├─ background/
│  │  └─ service-worker.js
├─ icons/
│  ├─ icon16.png
│  ├─ icon32.png
│  ├─ icon48.png
│  └─ icon128.png
├─ manifest.json
├─ README.md
└─ LICENSE
📋 Requisitos Técnicos
Manifest V3: A extensão utiliza a versão 3 do Manifest, seguindo as novas diretrizes do Chrome.

Permissões Mínimas: Aplica o princípio do menor privilégio, solicitando apenas as permissões necessárias (storage e tabs).

Compatibilidade: Desenvolvida para ser compatível com o Chrome 114+ e não possui dependências nativas.

👨‍💻 Como Instalar e Testar
Siga estes passos para carregar e testar a extensão no seu navegador em modo de desenvolvedor.

Acesse chrome://extensions na barra de endereço do seu navegador.

Ative o "Modo desenvolvedor" no canto superior direito.

Clique em "Carregar sem compactação".

Selecione a pasta raiz do projeto (<seu-repositorio>).

O ícone da extensão será adicionado à sua barra de ferramentas. Clique nele para abrir o popup e interagir com o projeto.

📜 Licença
Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.
