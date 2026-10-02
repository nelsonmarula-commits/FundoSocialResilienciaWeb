FUNDO SOCIAL RESILIÊNCIA — V3 WEB TEST

Conteúdo
- index.html: aplicação web
- app.js / styles.css: lógica e interface
- people.js: colaboradores e dependentes incorporados para teste
- manifest.webmanifest / sw.js: PWA e suporte offline
- assets/: logotipo

TESTE LOCAL
Por causa do Service Worker/PWA, recomenda-se servir a pasta por HTTP em vez de abrir index.html diretamente.
Exemplo com Python instalado:
  python -m http.server 8080
Depois abrir no navegador:
  http://localhost:8080

PUBLICAÇÃO NO GITHUB PAGES
1. Criar um repositório para o teste Web ou usar uma branch/pasta dedicada.
2. Carregar TODO o conteúdo desta pasta na raiz do repositório.
3. GitHub: Settings > Pages.
4. Em Build and deployment, selecionar Deploy from a branch.
5. Branch: main; Folder: /(root); Save.
6. Aguardar a publicação e abrir o endereço indicado pelo GitHub.

CREDENCIAIS DE DEMONSTRAÇÃO
- Perfis: Colaborador, Aprovador, Administração
- Palavra-passe: 1234

IMPORTANTE
Esta é uma versão de demonstração. Os dados ficam no armazenamento local do navegador. Ainda NÃO existe backend/base de dados central nem sincronização real entre dispositivos. Não usar para dados clínicos ou comprovativos reais nesta fase.
