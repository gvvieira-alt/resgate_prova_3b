# Resgate de Projeto - Avaliação 3B
**Aluno:** Gustavo Vieira

## Problemas Encontrados:
- **Erro de Sintaxe:** A função `buscarDados()` estava fechada antes do código do fetch, impedindo o clique no botão.
- **Erro de API:** A URL estava no singular (`/post`) e o correto para esta API é no plural (`/posts`).
- **Erro de Renderização:** O uso do `.map()` sem o `.join('')` causava a exibição de vírgulas entre os itens da lista.
- **Segurança do Navegador:** O protocolo `file://` bloqueava o Fetch (resolvido utilizando o Live Server).

## Correções Realizadas:
- Correção estrutural da função JavaScript e da URL da API.
- Adição do método `.join('')` para limpar a exibição da lista.
- **Melhoria (PLUS):** Implementação de CSS para exibir os resultados em "cards" organizados e modernos.
- Adição de tag de ícone para eliminar o erro 404 de favicon no console.
