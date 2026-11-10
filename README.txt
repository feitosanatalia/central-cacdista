# Central CACDista

Aplicativo gratuito e simples para organizar os estudos para o Concurso de Admissão à Carreira de Diplomata (CACD). Ele transforma o tempo de estudo em informação útil, usando cada **item do edital** como unidade central: Matéria → Item do edital → Sessão de estudo.

**Acesse o app:** https://SEU-USUARIO.github.io/central-cacdista/

## Recursos

- Painel do dia e fila de revisão
- Sessões de estudo com cronômetro, pausa e retomada (tempo bruto, pausas e tempo líquido)
- Registro de tipo de atividade, humor e nível de domínio
- Edital organizado por matéria, com status, prioridade, domínio e próxima revisão
- Importação de itens do edital por CSV
- Histórico e relatórios de estudo, com análise por matéria
- Registro de provas e simulados
- Caderno de erros
- Backup em JSON, exportação em CSV e tema claro/escuro
- Funciona offline e pode ser instalado como aplicativo (PWA)

## Como usar

1. Abra o link do app no navegador.
2. Escolha uma matéria e um item do edital.
3. Inicie o cronômetro e estude.
4. Ao encerrar, registre o tipo de atividade, o humor e o domínio.
5. Consulte o painel do dia para ver o que revisar.

## Como instalar

- **Computador (Chrome ou Edge):** clique no ícone de instalar na barra de endereço.
- **Android (Chrome):** menu ⋮ → "Instalar app" ou "Adicionar à tela inicial".
- **iPhone (Safari):** botão Compartilhar → "Adicionar à Tela de Início".

## Seus dados

Tudo fica salvo apenas no navegador do seu aparelho (`localStorage`). Os dados **não sincronizam** entre dispositivos e podem ser perdidos se você limpar os dados do navegador.

Faça **backup semanal** em Configurações e guarde o arquivo JSON em local seguro. Para usar em outro aparelho, importe esse backup.

## Como atualizar o app publicado

1. Substitua os arquivos `index.html` e `sw.js` no repositório.
2. Altere a versão do cache em `sw.js` (por exemplo, de `v3` para `v4`).
3. Recarregue o app com `Ctrl + Shift + R`.

## Arquivos do projeto

- `index.html`: o aplicativo (HTML, CSS e JavaScript)
- `manifest.json`: configurações de instalação (PWA)
- `sw.js`: funcionamento offline
- `icon-192.png` e `icon-512.png`: ícones do app

## Tecnologias

HTML, CSS e JavaScript puros, sem servidor, sem cadastro e sem custo. Publicado com GitHub Pages.

## Aviso

Projeto independente, sem vínculo com o Instituto Rio Branco, o Itamaraty ou o Cebraspe. Os conteúdos do edital devem ser sempre conferidos no documento oficial, pois podem conter omissões ou erros de transcrição.

## Créditos

Criado por Natália Feitosa com ajuda de i.a.