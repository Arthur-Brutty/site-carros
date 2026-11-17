# Universo de Carros

Projeto escolar em HTML5 sobre o universo dos filmes *Carros* e o personagem Relâmpago McQueen.

## Identificação

- Autor: Arthur de Oliveira
- Turma: DSM3
- Unidade curricular: não informada nos arquivos disponíveis do projeto
- Ano indicado no projeto: 2025

## Descrição

O site apresenta a história, os personagens e dados de lançamento de produções do universo de *Carros*. Também contém formulários fictícios de inscrição em um campeonato e de contato. O projeto usa somente HTML5, sem CSS, JavaScript, frameworks ou backend.

## Como abrir localmente

1. Baixe ou copie a pasta completa do projeto.
2. Mantenha os arquivos HTML e a pasta `img` na mesma estrutura.
3. Abra o arquivo `index.html` em um navegador atualizado.
4. Use o menu principal para navegar entre as páginas.

## Páginas

- `index.html`: apresentação do tema, personagens, listas e galeria de imagens.
- `sobre.html`: história, curiosidades, conteúdo complementar, glossário e fontes externas.
- `dados.html`: tabela de produções com formatos e datas de lançamento.
- `cadastro.html`: inscrição fictícia em um campeonato de corridas.
- `contato.html`: canais fictícios de atendimento e formulário de mensagem.

## Recursos de acessibilidade

- Link “Pular para o conteúdo” como primeiro elemento do `body` em todas as páginas.
- Estrutura com `header`, `nav`, um único `main` e `footer`.
- Idioma da página definido como português do Brasil.
- Títulos organizados hierarquicamente.
- Navegação identifica a página atual com `aria-current="page"`.
- Navegações possuem nomes acessíveis.
- Imagens informativas possuem texto alternativo; a imagem decorativa possui `alt=""`.
- Campos de formulário possuem `label` associado e validação nativa.
- Tabela usa `caption`, grupos estruturais e cabeçalhos com `scope`.

## Teste de navegação por teclado

Foi realizada uma verificação estrutural dos elementos focáveis e da ordem em que aparecem no código. O teste manual completo em navegador ainda deve ser executado: percorrer cada página com a tecla Tab, confirmar foco visível em todos os links e controles, testar os botões e verificar o link “Pular para o conteúdo”. O resultado não foi declarado como aprovado porque o ambiente não disponibilizou uma execução visual confiável do navegador.

## Fontes consultadas

- [Pixar - Carros](https://www.pixar.com/feature-films/cars)
- [Pixar - Nossa história](https://www.pixar.com/our-story)
- [Pixar - Curtas-metragens](https://www.pixar.com/short-films/)
- [Disney+ Press - Carros na Estrada](https://press.disneyplus.com/news/disney-plus-cars-on-the-road-debuts-on-disney-plus-day-september-8)
- [National Park Service - Route 66](https://www.nps.gov/subjects/travelroute66/index.htm)

## Imagens e licenças

As ilustrações SVG foram criadas especificamente para este projeto, sem copiar arquivos externos. Podem ser usadas e adaptadas neste trabalho escolar.

| Arquivo | Uso | Origem | Licença |
| --- | --- | --- | --- |
| `img/carro-vermelho.svg` | Imagem informativa de um carro de corrida genérico | Criação original para o projeto | Uso autorizado neste projeto escolar |
| `img/pista-corrida.svg` | Imagem informativa de uma pista | Criação original para o projeto | Uso autorizado neste projeto escolar |
| `img/bandeira.svg` | Imagem decorativa de uma bandeira quadriculada | Criação original para o projeto | Uso autorizado neste projeto escolar |

## Dificuldades e soluções

- A página inicial possuía marcação incompleta e problemas de codificação. O conteúdo válido foi preservado e a estrutura semântica foi corrigida.
- Alguns arquivos obrigatórios estavam vazios ou tinham nomes digitados incorretamente. Foram criadas as versões exigidas com nomes em minúsculas.
- A origem das imagens anteriores não estava documentada. Elas foram substituídas por ilustrações originais criadas para o projeto.
- As cinco páginas foram enviadas ao Nu HTML Checker oficial do W3C e retornaram zero erros ou avisos. O ambiente não disponibilizou Lighthouse nem um navegador automatizado confiável; as evidências visuais ainda precisam ser capturadas manualmente.

## Evidências ainda necessárias

Antes da entrega, capture manualmente:

1. A tela do resultado de cada uma das cinco páginas no [validador W3C](https://validator.w3.org/nu/). A validação automatizada retornou zero ocorrências, mas as capturas ainda precisam ser produzidas.
2. A aba Lighthouse do DevTools para cada página, especialmente a categoria Acessibilidade.
3. O DevTools mostrando `header`, `nav`, `main` e `footer` na estrutura de cada página.
4. Os formulários exibindo a validação nativa ao tentar enviar campos obrigatórios vazios.
5. A navegação completa por teclado, incluindo o link “Pular para o conteúdo”.

