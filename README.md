# Site Mage Telecom

Site institucional da **Mage Telecom**, provedor de internet em Águas Lindas de Goiás – GO.
MAGE TELECOM LTDA · CNPJ 48.527.149/0001-50 · Quadra 22, Lote 15, Sala 02.

## Estrutura

- `index.html` — página única com todo o CSS e JavaScript.
- `assets/logo-mage.webp` — logo com "TELECOM" escuro (fundos claros).
- `assets/logo-mage-branca.webp` — logo com "TELECOM" branco (fundos escuros e rodapé).
- `assets/foto-1-hero-celular.webp` — foto do topo.
- `assets/foto-2-combos-familia.webp` — banner da aba de combos.
- `assets/foto-3-casa-conectada.webp` — bloco "Até 800 Mega" nas vantagens.
- `assets/foto-4-tecnico-instalacao.webp` — bloco "Empresa de Águas Lindas" nas vantagens.

Para trocar uma foto, substitua o arquivo em `assets/` mantendo o mesmo nome.

## Seções

Topo em mosaico com recomendador de plano, abas Internet / Internet + Streaming
(com comparação de economia nos combos), vantagens, consulta de cobertura via
WhatsApp, teste de velocidade, dúvidas frequentes e rodapé com área do cliente.

## Onde editar

Tudo fica no bloco `<script>` no fim do `index.html`:

- `WHATSAPP` — número usado em todos os botões (DDI 55 + número).
- `AREA_CLIENTE_URL` — link da área do cliente / segunda via (Central do Assinante). Vazio = o botão abre o WhatsApp pedindo a segunda via.
- `PLANS` — velocidade, preço e textos de cada plano.
- `COMBOS` — combos e apps inclusos.
- `AVULSO` — preço dos apps assinados à parte, usado na conta de economia (consultado em out/2026).
- `APPS` — para usar a logo oficial de um app, preencha `img` com o caminho do arquivo em `assets/`.

## Publicar

Não há build nem dependências; as fontes vêm do Google Fonts.

**Pelo cPanel (recomendado):** em *Git Version Control*, clone este repositório e use
*Manage > Pull or Deploy > Deploy HEAD Commit*. O arquivo `.cpanel.yml` copia
`index.html` e `assets/` para a pasta pública definida em `DEPLOYPATH`.

**Manual:** envie `index.html` e a pasta `assets/` pelo Gerenciador de Arquivos.
