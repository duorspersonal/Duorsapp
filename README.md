# Duo RS Assessoria Esportiva

App web instalável (PWA) para gestão de alunos, treinos e financeiro.

## Estrutura
- `index.html`, `manifest.webmanifest`, `sw.js`: o aplicativo.
- `icons/`: ícones usados pelo app instalado (halter laranja).
- `branding/duo-rs/`: ícones e logo Duo RS (roxo e verde), em vários tamanhos.
- `branding/halter/`: ícones do halter laranja.
- `RESUMO-DO-PROJETO.md`: tudo que o app faz.

## Publicar no GitHub Pages
1. Crie um repositório público (ex.: `duors-app`).
2. Envie todos os arquivos e pastas deste pacote, mantendo `index.html` na raiz.
3. Em Settings > Pages, escolha "Deploy from a branch", branch `main`, pasta `/ (root)`.
4. Abra `https://SEU-USUARIO.github.io/duors-app/` no celular e instale.

## Links
- Convite de cadastro: botão Convidar (aba Alunos). Usa o endereço do próprio app.
- Acesso do aluno: perfil do aluno > Enviar app. O link leva o treino, os resultados, o plano e as mensagens do aluno. Para atualizar, envie um novo link.

Os dados ficam salvos no aparelho de quem usa. Não há servidor.
