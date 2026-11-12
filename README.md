# Mundo das Patas — Petshop

Projeto acadêmico da **Fase 1 de Fundamentos de Sistemas Web — PUCRS**. Site estático de um petshop fictício, desenvolvido exclusivamente em **HTML5**, com três páginas navegáveis.

**Autoria:** Gustavo da Silveira Costa — Fundamentos de Sistemas Web, PUCRS.

**Situação:** arquivos locais preparados e conferidos estruturalmente; publicação no GitHub e no GitHub Pages ainda não realizada. As instruções abaixo são para execução pelo estudante quando decidir publicar. A conferência visual no navegador local e o PDF da entrega acadêmica também estão pendentes.

## Objetivos e metas

**Objetivo geral:** desenvolver um site estático em HTML5 para apresentar os produtos e serviços do Petshop Mundo das Patas, com navegação organizada e informações claras ao usuário.

**Metas do projeto:**

1. Elaborar três páginas HTML5 conectadas por links relativos.
2. Apresentar dois produtos de cada categoria obrigatória, totalizando seis, com imagem, nome, descrição e preço.
3. Detalhar quatro modalidades de banho e tosa, com preço e indicação explícita da presença ou ausência de tele-busca.
4. Incluir cabeçalho, navegação, autoria, contato demonstrativo e rodapé em todas as páginas.
5. Documentar o projeto e, após decisão do estudante, publicar os arquivos no GitHub e testar o site no GitHub Pages.

## Funcionalidades de apresentação

- **Início:** apresentação do petshop e atalhos para as categorias e os serviços.
- **Produtos:** catálogo dividido em acessórios, rações não perecíveis e higiene e limpeza.
- **Serviços:** descrições e preços das quatro modalidades e explicação da tele-busca.
- **Navegação:** menus no cabeçalho e no rodapé, links entre páginas, atalhos para categorias e links para o conteúdo principal.

O cabeçalho apresenta o nome **Mundo das Patas — Petshop** e a frase “Carinho e cuidado para o dia a dia do seu pet.”. O conteúdo principal funciona como uma vitrine de produtos e serviços. Cada página mantém uma única observação acadêmica discreta no rodapé **Contato e informações**, junto da autoria, do contato demonstrativo e da navegação.

O site não possui compra, carrinho, pagamento, cadastro, login, formulário ou agendamento. Produtos, preços, serviços e contato são fictícios. O endereço `contato@mundodaspatas.example` é demonstrativo e não recebe mensagens.

## Estrutura dos arquivos

```text
petshop-mundo-das-patas/
├── index.html
├── produtos.html
├── servicos.html
├── imagens/
│   ├── coleira-ajustavel.png
│   ├── mordedor-borracha.png
│   ├── racao-caes.png
│   ├── racao-gatos.png
│   ├── shampoo-caes.png
│   ├── tapete-higienico.png
│   └── ORIGEM.md          (registro da geração das imagens)
├── README.md
├── .gitignore
├── AGENTS.md              (orientações locais; não enviar)
└── CONTEXTO_FASE1.md      (contexto acadêmico local; não enviar)
```

Não há dependências, instalação, compilação, CSS, Bootstrap, JavaScript, biblioteca de frontend ou back-end. O site não precisa de Node.js, Python ou servidor para ser aberto localmente.

## Como abrir localmente

1. Abra a pasta do projeto no Explorador de Arquivos.
2. Dê dois cliques em **`index.html`**. Se necessário, use **Abrir com** e escolha seu navegador.
3. Navegue pelos links **Produtos** e **Serviços**.
4. Mantenha os três arquivos HTML e a pasta `imagens/` juntos, respeitando os nomes dos arquivos.

O navegador abrirá um endereço local iniciado por `file:///`. Isso é esperado. O site usa a apresentação padrão do navegador porque a Fase 1 não permite CSS.

## Catálogo e serviços

| Categoria | Produto | Preço fictício |
| --- | --- | --- |
| Acessórios | Coleira ajustável para cães | R$ 39,90 |
| Acessórios | Brinquedo mordedor de borracha | R$ 24,90 |
| Rações não perecíveis | Ração seca para cães adultos — 3 kg | R$ 69,90 |
| Rações não perecíveis | Ração seca para gatos adultos — 3 kg | R$ 79,90 |
| Higiene e limpeza | Shampoo para cães — 500 ml | R$ 29,90 |
| Higiene e limpeza | Tapete higiênico — 30 unidades | R$ 49,90 |

| Serviço | Tele-busca | Preço fictício |
| --- | --- | --- |
| Banho | Sem tele-busca | R$ 50,00 |
| Banho | Com tele-busca | R$ 70,00 |
| Banho e tosa | Sem tele-busca | R$ 90,00 |
| Banho e tosa | Com tele-busca | R$ 110,00 |

Nas modalidades com tele-busca, o transporte de ida e volta está incluído no valor apresentado. Sem tele-busca, o tutor leva e busca o pet.

## Imagens: origem e uso

As seis imagens PNG foram geradas especificamente para este projeto com a ferramenta integrada **OpenAI Image Generation (imagegen)**, a partir de descrições dos produtos. São imagens ilustrativas em estilo fotográfico, e não fotografias de mercadorias reais. Não foram copiadas de lojas ou bancos de imagens e não representam marcas comerciais.

Os arquivos são locais: as páginas não dependem de URLs externas para carregar as imagens. A origem por inteligência artificial é registrada nesta documentação, e os prompts completos estão em [imagens/ORIGEM.md](imagens/ORIGEM.md). Não se atribui uma licença Creative Commons nem autoria fotográfica humana a esses arquivos.

Descrição-base usada na geração: imagem quadrada de catálogo de um petshop fictício, produto inteiro centralizado, fundo branco, iluminação suave, sombra discreta, sem pessoas, marca real, marca-d'água ou preço. Os pedidos específicos foram:

| Arquivo | Conteúdo solicitado |
| --- | --- |
| `coleira-ajustavel.png` | Coleira de nylon verde-azulada em formato oval, regulagem, fecho preto e argola metálica; sem texto. |
| `mordedor-borracha.png` | Mordedor de borracha laranja em formato de osso, com textura; sem texto. |
| `racao-caes.png` | Pacote laranja e creme, grãos secos e silhueta de cão; textos “CÃES ADULTOS” e “3 kg”. |
| `racao-gatos.png` | Pacote verde-azulado e creme, grãos secos e silhueta de gato; textos “GATOS ADULTOS” e “3 kg”. |
| `shampoo-caes.png` | Frasco com líquido verde-claro, tampa branca e silhueta de cão; textos “SHAMPOO PARA CÃES” e “500 ml”. |
| `tapete-higienico.png` | Tapete branco com borda azul, tapetes dobrados e pacote; textos “TAPETES HIGIÊNICOS” e “30 unidades”. |

## Decisões de HTML5

- `<!DOCTYPE html>` identifica o documento HTML5. `lang="pt-BR"`, UTF-8 e `viewport` definem idioma, codificação e área de visualização.
- `header`, `nav`, `main` e `footer` identificam as regiões de cada página. Os menus são repetidos nos três arquivos porque não há código para gerar componentes nesta fase.
- `small` identifica a observação acadêmica no rodapé, sem estilos CSS.
- Há um `h1` por página; `h2` organiza as seções e `h3` identifica cada produto ou serviço. `section` agrupa categorias e `article` delimita cada item.
- `img` usa `src` relativo e `alt` descritivo. `width` e `height` são atributos HTML válidos que reservam espaço para as imagens; não são CSS.
- `aria-current="page"` informa a página atual, e os rótulos de navegação diferenciam os menus. O link “Ir para o conteúdo” permite saltar diretamente ao `main`.
- Links como `produtos.html#higiene` apontam a arquivos e identificadores existentes. Nenhum caminho do site começa por `/` ou depende de uma unidade do computador, preservando o funcionamento sob o subdiretório do GitHub Pages.

## Publicação no GitHub Pages — execução pelo estudante

Nenhum repositório remoto foi criado e nenhum `git push` foi executado durante a preparação. O caminho mais simples é enviar os arquivos pela interface do GitHub:

1. Crie um repositório público chamado `petshop-mundo-das-patas` na sua conta.
2. Envie `index.html`, `produtos.html`, `servicos.html`, `README.md`, `.gitignore` e a pasta `imagens/` com os seis PNGs e `ORIGEM.md`, preservando sua estrutura. O `index.html` precisa ficar na raiz.
3. Confira os arquivos e confirme o envio na branch `main`.
4. Em **Settings → Pages → Build and deployment**, selecione **Deploy from a branch**; escolha **main** e **/(root)** e clique em **Save**. Esse procedimento segue a [documentação oficial de publicação do GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).
5. Aguarde a conclusão da publicação e abra o endereço efetivamente exibido pelo GitHub Pages.
6. Teste as três páginas, todos os menus, os atalhos para categorias e as seis imagens pela URL pública, inclusive em uma janela privativa.
7. Registre os links reais do repositório e do site no template acadêmico. Atualize a situação deste README somente depois de verificar a publicação.

O endereço esperado tem o formato `https://SEU-USUARIO.github.io/petshop-mundo-das-patas/`; isso é apenas um exemplo de formato, não uma URL publicada ou testada.

Envie somente os arquivos listados. Não envie PDFs, capturas de aulas, credenciais, dados pessoais de contato ou materiais proprietários da universidade. O `.gitignore` ajuda a excluir materiais locais ao usar Git; ele não filtra arquivos escolhidos manualmente para upload pelo navegador.

## Verificação realizada

Na preparação e na revisão textual de 10/11/2026, foram conferidos diretamente nos arquivos:

- As três páginas com UTF-8, idioma `pt-BR`, viewport, títulos, hierarquia de cabeçalhos e estrutura semântica.
- Os 32 links relativos, incluindo seus arquivos de destino e identificadores de âncoras, com capitalização consistente.
- Os seis produtos, dois por categoria, com descrição, preço planejado e imagem correspondente com texto alternativo.
- Os seis PNGs, abertos e decodificados com sucesso, além da inspeção visual das imagens geradas.
- Os quatro serviços, com descrições, preços e indicação de tele-busca.
- Os menus de cabeçalho e rodapé, autoria e contato demonstrativo nas três páginas.
- O aviso acadêmico restrito ao rodapé, com os textos de apresentação ajustados e todo o conteúdo das categorias, produtos e serviços preservado.
- A ausência de CSS, JavaScript, formulários e arquivos PDF no projeto.

**Limite da verificação:** o navegador integrado bloqueou URLs `file:///` por sua política de segurança. Portanto, a renderização das páginas e os cliques no navegador ainda precisam ser conferidos manualmente pelo estudante. A inspeção estrutural não é uma certificação de conformidade por um validador oficial de HTML5. Nenhuma URL pública foi publicada ou testada.

## Conferência da rubrica e entrega acadêmica

| Critério | Pontos | Evidência no projeto | Etapa restante |
| --- | --- | --- | --- |
| Definição dos objetivos e metas | 0,5 | Seção “Objetivos e metas” deste README | Revisar e transpor para o template acadêmico. |
| Cabeçalho e menu de navegação | 0,6 | Nome do petshop, apresentação e menu nas três páginas | Repetir a conferência na URL pública. |
| Conteúdo do sistema web | 1,5 | Seis produtos com imagem, descrição e preço; três categorias; quatro serviços com descrição, preço e tele-busca explícita | Repetir a conferência na URL pública. |
| Rodapé, contato e outras informações | 0,4 | Autoria de Gustavo da Silveira Costa, aviso de demonstração, contato fictício e navegação em todas as páginas | Repetir a conferência na URL pública. |

Checklist para a revisão manual pelo estudante:

- [ ] Abrir as três páginas e navegar pelos menus do cabeçalho e rodapé.
- [ ] Conferir os atalhos para as três categorias e para o conteúdo principal.
- [ ] Verificar os seis produtos, suas imagens, descrições e preços.
- [ ] Conferir as quatro modalidades de serviço e a indicação de tele-busca.
- [ ] Confirmar que não há CSS, JavaScript, formulários ou funções de compra.
- [ ] Publicar os arquivos autorizados no GitHub e habilitar o GitHub Pages.
- [ ] Testar o endereço público e registrar as URLs reais.
- [ ] Preencher o template oficial da PUCRS com identificação, objetivos, metas e os dois links, exportar para PDF e entregar no ambiente da disciplina.

O template oficial não foi fornecido nesta pasta; este projeto não inclui nem substitui o PDF de entrega. A conferência usa os requisitos resumidos pelo estudante e não garante nota. Em caso de divergência, prevalece o enunciado oficial da PUCRS.
