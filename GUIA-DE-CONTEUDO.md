# Guia de conteúdo — Ingrid Nascimento

Este site já tem uma estrutura completa de conversão. Ele **não publica resultados, depoimentos, valores ou materiais inexistentes**: tudo que aparece entre colchetes (`[ ]`) é um espaço para você preencher antes de divulgar.

## Ordem recomendada de preenchimento

1. **Serviços** — preencha as quatro páginas em `servicos/`.
2. **Depoimentos autorizados** — revise os três trechos já selecionados na seção “Feedbacks reais”.
3. **Vídeo** — grave um material curto antes de pedir para recolocar esta seção no site.
4. **Materiais gratuitos** — publique os PDFs antes de criar cards de download.
5. **Fotos** — envie registros profissionais e autorizados para uma galeria futura.

---

## Onde editar cada parte

### 1. Serviços detalhados

Páginas prontas:

- `servicos/curriculo-estrategico.html`
- `servicos/posicionamento-linkedin.html`
- `servicos/preparacao-entrevistas.html`
- `servicos/direcionamento-carreira.html`

As páginas de serviço estão temporariamente marcadas como **`noindex`** para não aparecerem no Google com conteúdo vazio. Quando cada página estiver completa, remova a linha `<meta name="robots" content="noindex, nofollow">` e inclua sua URL no `sitemap.xml`.

Em cada página, troque todos os textos entre colchetes:

- `[Descreva para quem este serviço faz sentido.]`
- `[Entrega ou etapa 01]`
- `[Informe somente dados confirmados.]`
- perguntas e respostas frequentes;
- espaço de foto, vídeo ou captura autorizada.

**Não publicar:** preços não confirmados, prazos que não consegue cumprir, promessas de contratação, promoção ou garantia de resultado.

### 2. Depoimentos e casos

A seção **“Feedbacks reais”** no `index.html` possui três trechos curtos selecionados dos feedbacks enviados. Eles usam identidade preservada para proteger clientes.

Antes de publicar nomes, fotos de conversas ou @ de clientes, confirme a autorização. Para futuros casos, prefira este formato:

- momento/contexto inicial;
- tema trabalhado;
- aprendizado ou percepção autorizada;
- sem dados de empresa, salário, processos seletivos ou informações sensíveis.

### 3. Vídeo de apresentação

A seção de vídeo foi retirada da página principal para deixá-la mais leve. Recoloque somente quando o vídeo estiver pronto.

Sugestão de roteiro — 30 a 45 segundos:

1. Quem é a Ingrid e com quem ela trabalha;
2. qual tipo de conversa/problema ela ajuda a organizar;
3. como a pessoa pode iniciar uma conversa;
4. convite simples para o WhatsApp.

**Gravação:** áudio limpo importa mais que equipamento. Grave perto de uma janela, em ambiente silencioso, com olhar na câmera. Evite promessas como “vou conseguir uma vaga para você”.

Formatos recomendados:

- Vertical: 1080 × 1920 (9:16) para celular;
- Horizontal: 1920 × 1080 (16:9) para desktop;
- Legendas revisadas;
- Capa com rosto visível e fundo sem excesso de informação.

### 4. Fotos

A foto de palestra atual está em `assets/ingrid-palestra.jpg`.

Espaços adicionais reservados na seção “Histórias reais”:

- foto em evento/palestra;
- bastidor autorizado;
- retrato ou registro profissional.

Para cada foto nova:

- exporte em JPG ou WebP;
- envie em pelo menos 1600 px no lado maior;
- use fotos com rosto e mãos visíveis, boa luz e contexto profissional;
- obtenha autorização de outras pessoas visíveis;
- evite fotos com telas contendo dados privados.

### 5. Materiais gratuitos

Quando os materiais existirem, crie cards simples para eles:

- `[Checklist de LinkedIn]`
- `[Guia de entrevista]`
- `[Roteiro de carreira]`

Não anuncie um PDF antes de ele existir. Quando o arquivo estiver pronto:

1. salve o PDF em `assets/materiais/`;
2. altere o texto e o botão do card correspondente;
3. substitua o link do WhatsApp pelo link do PDF ou por uma página de cadastro;
4. revise o PDF no celular antes de publicar.

### 6. Diagnóstico inicial

A seção **“Em qual ponto você quer ganhar clareza?”** tem quatro opções. Ao escolher uma, a pessoa é direcionada ao WhatsApp com o assunto preenchido.

Você pode editar os textos das opções, mas mantenha no máximo quatro ou cinco escolhas. Isso reduz dúvida e deixa a decisão rápida.

---

## Estrutura de conversão já pronta

- Botão de WhatsApp no hero;
- botão flutuante de WhatsApp;
- formulário de contato que monta mensagem de WhatsApp;
- diagnóstico de assunto;
- links por serviço;
- interesse nos materiais;
- páginas individuais de serviço;
- espaços de depoimentos, casos, fotos e vídeo.

O site também cria eventos internos de interação (`ingrid:track`), mas **nenhuma plataforma de analytics foi conectada**. Isso evita afirmar que há rastreamento quando não há.

### Quando conectar analytics

Com consentimento e conta configurada, um desenvolvedor pode ouvir esses eventos para enviar conversões ao Google Analytics, Meta Pixel ou outra ferramenta:

- `hero_whatsapp`
- `floating_whatsapp`
- `contact_whatsapp`
- `contact_form_whatsapp`
- `diagnostic_selection`
- `diagnostic_whatsapp`
- `resource_interest`

Faça isso somente depois de decidir qual ferramenta será usada e de publicar uma política de privacidade adequada.

---

## SEO — o que fazer depois

Para cada serviço, escreva uma página verdadeira com:

- título específico e natural;
- resumo do serviço;
- dúvidas frequentes reais;
- imagem própria;
- CTA para WhatsApp;
- termos que as pessoas realmente usam para buscar ajuda.

Ideias de temas de conteúdo, sem promessas:

- como organizar experiências no currículo;
- o que revisar no LinkedIn;
- como se preparar para contar a própria trajetória;
- perguntas para refletir antes de uma mudança de carreira.

Evite criar artigos em quantidade sem profundidade. Um bom conteúdo por mês é mais útil que muitos textos genéricos.

---

## Direção de design recomendada

### Eu manteria

- a paleta atual: preto, areia/taupe e laranja somente como acento;
- fotos reais em vez de bancos de imagem;
- tipografia editorial e bastante espaço entre blocos;
- animações discretas e lentas;
- CTA direto para conversa, não para promessa de resultado.

### Eu adicionaria depois

- uma capa de vídeo real;
- depoimentos autorizados;
- uma foto profissional atualizada para cada página de serviço;
- uma sessão de perguntas frequentes com respostas reais;
- materiais próprios em PDF, somente quando concluídos;
- uma política de privacidade quando houver captação de e-mail ou analytics.

### Eu não faria

- não colocaria contadores inventados (“X clientes”, “Y vagas”);
- não usaria logos de empresas sem autorização;
- não exibiria conversas, currículos ou telas de clientes sem permissão;
- não usaria carrosséis automáticos;
- não transformaria cada seção em um CTA; o site precisa respirar;
- não aumentaria mais as animações: o conteúdo e as fotos reais devem ser o foco.

---

## Checklist antes de divulgar

- [ ] Todos os textos entre colchetes foram trocados ou removidos.
- [ ] Depoimentos e fotos foram autorizados.
- [ ] Links dos PDFs funcionam no celular.
- [ ] Páginas de serviço têm escopo real e atual.
- [ ] WhatsApp, e-mail e redes sociais foram revisados.
- [ ] O vídeo tem legenda e áudio compreensível.
- [ ] O site foi revisado em um celular real.
- [ ] Não há promessas ou dados confidenciais.
