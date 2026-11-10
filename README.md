# API da Escola New Tech (material de aula)

Site estático usado no Módulo 3 do Green Belt. Contém `index.html` (documentação), `catalogo.json`,
`cursos/NT-xxx.json` (um arquivo por curso) e `politicas.json`. A Escola New Tech é fictícia.

## Como publicar no GitHub Pages (cerca de 5 minutos)

1. Crie um repositório **público** no GitHub, por exemplo `escola-new-tech`.
2. Envie o conteúdo desta pasta para a raiz do repositório (botão **Add file › Upload files**).
3. Em **Settings › Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em alguns minutos o site fica disponível em `https://SEU-USUARIO.github.io/escola-new-tech/`.
5. Teste no navegador: `.../catalogo.json` e `.../cursos/NT-102.json` devem abrir; `.../cursos/NT-999.json` deve dar 404.
6. Publique no Classroom o endereço base (sem `/catalogo.json` no final) e troque o valor de `BASE_URL`
   na célula de preparação do notebook da Aula 2 antes de compartilhar com a turma.

Para atualizar datas de turmas, edite `catalogo.json` e os arquivos em `cursos/`, e faça commit.
