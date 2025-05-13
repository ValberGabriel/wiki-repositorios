📚 Wiki de Repositórios GitHub
Este projeto foi desenvolvido como parte da formação em React da DIO.me por Valber Gabriel. O objetivo foi criar uma wiki de repositórios do GitHub usando React e JavaScript, com consumo da API pública do GitHub.
🚀 Tecnologias utilizadas
- React (JavaScript)
- API REST do GitHub
- CSS puro (modularizado)
🧠 Funcionalidades
- Buscar repositórios públicos do GitHub pelo nome (formato `usuario/repositorio`)
- Exibir uma lista dos repositórios pesquisados
- Prevenir repositórios duplicados
- Exibir mensagens de erro em casos de falha na busca
- Acessar os repositórios diretamente via link
📁 Estrutura de pastas
src/
├── components/
│   └── RepositorioCard.jsx   # Componente para exibir repositórios
├── styles/
│   └── App.css               # Estilos da aplicação
├── App.jsx                   # Componente principal
├── index.js                  # Ponto de entrada da aplicação
└── index.css                 # Estilos globais (opcional)
💡 Como executar o projeto
1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/wiki-repositorios.git
```

2. Acesse a pasta do projeto:
```bash
cd wiki-repositorios
```

3. Instale as dependências:
```bash
npm install
```

4. Execute o projeto:
```bash
npm start
```
> A aplicação será aberta em http://localhost:3000
📌 Exemplo de uso
Digite algo como:

facebook/react

Clique em “Adicionar” e o repositório aparecerá na sua lista com nome, descrição e link direto para o GitHub.
🛠 Melhorias futuras (ideias)
- Autenticação com conta do GitHub
- Salvamento dos repositórios em localStorage
- Remoção de repositórios da lista
- Tema escuro/claro
- Responsividade para dispositivos móveis
🧑💻 Autor
Desenvolvido por Valber Gabriel, aluno da DIO.me, como parte da formação em React.js.
