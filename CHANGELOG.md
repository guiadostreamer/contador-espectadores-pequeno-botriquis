# Histórico de alterações

Todas as mudanças importantes do **Botriquis** serão documentadas neste arquivo.

## [1.0.0] — 2026-11-11

### Lançamento inicial

- Contador horizontal compacto e translúcido com um único fundo visível.
- Ícones Kick, Twitch, YouTube e Facebook tratados visualmente; logo roxo e branco da Twitch fornecido pelo autor e incorporado ao CSS.
- Total de espectadores à direita; contadores individuais ocultos visualmente.
- Integração com os itens e os dados do widget nativo **Contador de espectadores**, da Streamlabs.
- Soma automática e animação discreta de atualização.
- Variáveis CSS para ajustes de proporção, transparência e tipografia.
- README de instalação e licença de uso gratuito com restrições.

### Temas visuais

- `css_01_original_claro.txt`: tema claro original, preservando o visual aprovado.
- `css_02_preto_transparente.txt`: alternativa com cápsula preta a 22% de opacidade.
- Os dois temas compartilham exatamente o mesmo HTML e JavaScript.

### Revisão pré-publicação — 2026-11-23

- Alinhada a mecânica de contagem à implementação do **Square Total** do Guia do Streamer, validada ao vivo pelo autor.
- Atualizado `html.txt` para incluir a classe exclusiva `.platform-source-count` nos contadores individuais, preservando `.platform-count` para ocultação pelo CSS.
- Atualizado `js.txt` para usar a mesma leitura, soma, observação por `MutationObserver`, inicialização e transição numérica do Square Total.
- Mantidos inalterados os arquivos `css_01_original_claro.txt` e `css_02_preto_transparente.txt`, incluindo cores, logos e dimensões.
- Mantidas exatamente as duas imagens de prévia aprovadas pelo autor: `preview-botriquis-claro.png` e `preview-botriquis-preto-transparente.png`.
- Corrigida a documentação: removida a referência antiga a `css.txt`, que não faz parte do pacote final.
- Atualizado o README para documentar o alinhamento ao Square Total.

### Validação e limitações

- Sintaxe do JavaScript verificada.
- Visual base aprovado em captura da Streamlabs apresentada pelo autor; a revisão não altera os CSS.
- Square Total já testado ao vivo pelo autor, mas **o Botriquis ainda requer validação ao vivo própria**.
- Logo do Facebook preparado por CSS; ainda não testado com Facebook conectado.
- Não há garantia de compatibilidade contínua com eventuais mudanças na Streamlabs ou nas plataformas.
