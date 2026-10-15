# Status III — Equipamentos Táticos

Projeto completo em HTML, CSS e JavaScript, pronto para GitHub e Vercel.
Não precisa de Node.js, npm, banco de dados ou variáveis de ambiente.

## 1. Enviar ao GitHub

1. Extraia o arquivo ZIP no computador.
2. Crie um repositório no GitHub (exemplo: status-iii).
3. Selecione **Add file → Upload files**.
4. Abra a pasta extraída e envie **os arquivos de dentro dela**, incluindo a pasta `assets`.
5. Faça o commit.

**Importante:** `index.html` e `vercel.json` devem aparecer diretamente na página inicial do repositório. Não envie apenas o ZIP e não coloque o projeto dentro de outra pasta.

## 2. Hospedar na Vercel

1. Entre na Vercel e selecione **Add New → Project**.
2. Importe o repositório do GitHub.
3. Confira:

| Campo | Valor |
| --- | --- |
| Framework Preset | Other |
| Root Directory | Raiz do repositório (deixe o padrão) |
| Build Command | Vazio |
| Output Directory | . |
| Install Command | Vazio |
| Environment Variables | Nenhuma |

O arquivo `vercel.json` já inclui as configurações do site estático.

4. Clique em **Deploy**.
5. Ao concluir, abra o endereço fornecido pela Vercel.

## Se aparecer erro 404

Confira se `index.html`, `vercel.json` e `assets/` estão na raiz do repositório. Se você enviou uma pasta envolvendo o projeto, mova o conteúdo dela para a raiz ou selecione essa pasta em Root Directory. Mantenha o preset Other e a saída como ponto (`.`).

## O que está incluído

- Tema preto com letras douradas e logotipo fornecido.
- Sete grupos de produtos: uniforme tático, capa modular, camisa cinza bandeirante, insígnias, gorro, garrafas e caneca térmica.
- Filtros por categoria e galeria de imagens.
- WhatsApp: (15) 99666-8304.
- Instagram: @status3equipamentotaticos.
- As imagens de facas táticas e spray de defesa não integram esta versão.

## Alterações futuras

- `index.html`: textos, seções e Instagram.
- `style.css`: cores, tamanhos e aparência.
- `app.js`: produtos, fotos da galeria e número do WhatsApp.
- `assets/`: imagens originais incluídas no site.

Para trocar o telefone, atualize todas as ocorrências do número em `index.html` e `app.js`. Para alterar o catálogo, edite a lista `products` em `app.js`; ao adicionar ou remover itens, ajuste também a contagem do filtro Todos em `index.html`.

Você pode abrir `index.html` diretamente no navegador para conferir o site. Após publicar, teste os filtros, a galeria, o fechamento pelo botão e pela tecla Esc, o Instagram e os botões do WhatsApp no celular e no computador.

## Verificações realizadas

Sintaxe do JavaScript, referências às imagens e aos arquivos locais, links de contato e integridade do ZIP. Não foi realizado deploy na sua conta Vercel nem teste visual no navegador nesta exportação.

## Documentação oficial

https://vercel.com/docs/deployments/configure-a-build
https://vercel.com/docs/project-configuration
