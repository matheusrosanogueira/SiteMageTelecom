# Site Mage Telecom

Site institucional da **Mage Telecom**, provedor de internet em Águas Lindas de Goiás – GO.
MAGE TELECOM LTDA · CNPJ 48.527.149/0001-50 · Quadra 22, Lote 15, Sala 02.

## Estrutura

- `index.html` — página única com todo o CSS e JavaScript.
- `assets/logo-mage.webp` — logo com "TELECOM" escuro (fundos claros).
- `assets/logo-mage-branca.webp` — logo com "TELECOM" branco (fundos escuros e rodapé).

## Seções

Topo com recomendador de plano, planos de 200 a 800 Mega, combos com streaming
(com comparação de economia), vantagens, consulta de cobertura via WhatsApp,
dúvidas frequentes e rodapé com contato.

## Onde editar

Tudo fica no bloco `<script>` no fim do `index.html`:

- `WHATSAPP` — número usado em todos os botões (DDI 55 + número).
- `PLANS` — velocidade, preço e textos de cada plano.
- `COMBOS` — combos e apps inclusos.
- `AVULSO` — preço dos apps assinados à parte, usado na conta de economia (consultado em out/2026).
- `APPS` — para usar a logo oficial de um app, preencha `img` com o caminho do arquivo em `assets/`.

## Publicar

Basta enviar `index.html` e a pasta `assets/` para a pasta pública da hospedagem
(ex.: `public_html`). Não há build nem dependências; as fontes vêm do Google Fonts.
