# Restaurante PontoBR — Design Spec & Page Content

Based on the reference mockups (desktop web + mobile app), adapted for **Restaurante PontoBR** (Traditional Brazilian cuisine, focusing on churrasco and seafood). Content is written in **Portuguese (BR)**.

---

## 1. Visual Design Analysis

### Color Palette
| Role | Color | Notes |
|---|---|---|
| Background (base) | Warm cream / off-white `#FDF3E7` | Softens the whole layout, food photography pops against it |
| Primary accent (CTA) | Flame orange `#EE6C1F` → `#D64500` gradient | Used on all buttons, badges, active nav states (fits the churrasco/fire theme) |
| Dark surface (hero/banner) | Near-black charcoal `#150D0B` – `#1A0F0C` | High contrast for hero text, evokes the traditional grill/brasa |
| Text — primary | Very dark brown/black `#1C1310` | Body copy, headings on light background |
| Text — on dark | White / cream `#FFF7EE` | Hero copy, banner copy |
| Success/Save badge | Red `#E23D28` | "OFERTA", limited-time tags |
| Star rating | Gold/yellow `#F5A623` | Rating stars only, used sparingly |

### Typography
- **Headlines:** Bold, condensed-ish sans-serif (e.g., Poppins Bold / Sora Bold) — confident and welcoming.
- **Body/description:** Regular-weight sans-serif, generous line-height for readability (e.g., Inter or Manrope).
- **Price tags:** Bold, paired with the brand accent color or plain black.
- **Badges:** Small caps or uppercase, tiny pill-shaped tags, high contrast.

### Layout Components (Desktop)
1. **Top bar** — logo + friendly greeting ("Olá, seja bem-vindo! 👋") on the left, center nav (Home / Cardápio / Ofertas / Reservas / Sobre / Contato), right cluster: notification bell, cart icon, CTA button "Fazer Pedido"
2. **Search bar** — full-width pill search input with a filter/sliders icon on the right
3. **Hero carousel** — large dark rounded-corner banner, split layout: bold headline + subcopy + CTA on the left, hero food photography (Picanha na brasa / Peixes) bleeding off the right edge.
4. **Category strip** — horizontal row of circular icon buttons (Todos / Churrasco / Peixes / Porções / Bebidas / Sobremesas), active state highlighted in accent orange with underline.
5. **Product cards (grid of 3)** — white/cream rounded cards: badge top-left, product photo, name, short description, star rating, price, circular "+" add-to-cart button.
6. **Promo banner (full width, dark)** — "Oferta Exclusiva" tag, big discount, food photo bleeding right, CTA button.
7. **Trust strip (4-column icons)** — Tradição e Sabor / Ingredientes Frescos / Ambiente Familiar / Atendimento Premium.

### Layout Components (Mobile)
- Condenses to a **single column, stacked vertically**.
- Top bar: hamburger menu icon, logo, cart icon.
- Search bar full-width below top bar.
- Hero banner stacks headline over a smaller/cropped hero image.
- Category icons scroll horizontally (swipeable).
- Product cards stack **full-width**, image left / info right (row layout).
- **Bottom tab bar (fixed)** replaces the desktop top nav: Início / Menu / Ofertas / Reservas / Perfil.

---

## 2. Page Content

### 🏠 Home

**Hero**
> ### O Verdadeiro Sabor do Brasil
> Churrasco na brasa, peixes frescos e acompanhamentos com aquele gostinho de casa. Tradição e qualidade todos os dias.
>
> **[ Ver Cardápio → ]**

**Categorias**
`Todos` · `Churrasco` · `Peixes` · `Porções` · `Acompanhamentos` · `Bebidas` · `Sobremesas`

**Destaques da Casa**
| Badge | Item | Descrição | Avaliação | Preço |
|---|---|---|---|---|
| MAIS VENDIDO | Picanha Completa | Picanha na brasa, arroz, feijão, farofa especial e vinagrete. (Serve 2) | ⭐ 4.9 (12.5K+) | R$ 139,90 |
| POPULAR | Tilápia Grelhada | Filé de tilápia com legumes no vapor e arroz de brócolis. | ⭐ 4.7 (8.7K+) | R$ 79,90 |
| IMPERDÍVEL | Churrasco Misto | Mix de carnes nobres grelhadas com fritas e farofa. | ⭐ 4.8 (6.3K+) | R$ 119,90 |

**Banner de Oferta**
> **ALMOÇO EXECUTIVO — A partir de R$ 39,90**
> Pratos bem servidos com qualidade PontoBR, de segunda a sexta.
> **[ Peça Agora → ]**

**Por que escolher o PontoBR**
- 🔥 **Churrasco de Verdade** — cortes nobres na brasa
- 🐟 **Peixes Frescos** — receitas tradicionais e saborosas
- 👨‍👩‍👧‍👦 **Ambiente Familiar** — perfeito para toda a família
- 🛵 **Delivery Rápido** — o sabor do restaurante na sua casa

---

### 🥩 Cardápio (Menu)

**Churrasco (Na Brasa)**
- **Picanha Completa** — Acompanha arroz, feijão, farofa especial da casa e vinagrete — R$ 139,90
- **Baby Beef** — Corte macio acompanhado de fritas e arroz à grega — R$ 109,90
- **Contra Filé** — Acompanha arroz branco, feijão tropeiro e mandioca frita — R$ 99,90
- **Chorizo** — Bife de chorizo argentino com batatas rústicas e chimichurri — R$ 115,90
- **Churrasco Misto** — Seleção de carnes (picanha, linguiça, frango e lombo) com acompanhamentos tradicionais — R$ 119,90

**Peixes**
- **Moqueca de Tamboril** — Deliciosa moqueca com azeite de dendê, leite de coco, arroz branco e pirão — R$ 149,90
- **Filé de Tilápia Grelhado** — Com purê de batatas e legumes salteados — R$ 79,90
- **Bacalhau à Moda da Casa** — Posta de bacalhau no azeite com batatas, pimentões, ovos e azeitonas — R$ 169,90

**Porções e Acompanhamentos**
- Farofa Especial da Casa — R$ 15,90
- Batata Frita (P/M/G) — R$ 18,90 / R$ 24,90 / R$ 32,90
- Mandioca Frita com Queijo — R$ 28,90
- Bolinho de Bacalhau (6 unidades) — R$ 35,90
- Arroz de Brócolis — R$ 18,90

**Bebidas**
- Caipirinha de Limão / Maracujá / Morango — R$ 22,90
- Chopp Artesanal — R$ 12,90
- Refrigerantes e Sucos Naturais — a partir de R$ 8,90

**Sobremesas**
- Pudim de Leite Condensado — R$ 14,90
- Brigadeirão — R$ 16,90
- Petit Gâteau com Sorvete — R$ 22,90

---

### 🔥 Ofertas (Offers)

- **Happy Hour:** Chopp em dobro e descontos em porções, de terça a sexta (18h às 20h).
- **Festival de Peixes:** Desconto de 15% em todos os pratos de peixe às quartas-feiras.
- **Programa de Fidelidade:** Acumule pontos a cada pedido e troque por pratos e sobremesas grátis no nosso app exclusivo.

---

### 👨‍🍳 Sobre Nós (About Us)

**Nossa História**
> O Restaurante PontoBR nasceu da paixão pela culinária brasileira autêntica. Somos conhecidos por servir os melhores cortes de carne grelhados na brasa e peixes frescos, tudo preparado com o carinho e o sabor que só a nossa cozinha tem.

**Nossa Missão**
> Proporcionar uma experiência gastronômica inesquecível, celebrando os sabores do Brasil em um ambiente acolhedor e familiar.

---

### 📅 Reserva (Reservation)

**Reserve sua mesa**
> Venha celebrar momentos especiais no Restaurante PontoBR. Preencha os dados abaixo e confirmaremos sua reserva.

**Campos do formulário**
- Nome completo
- Telefone / WhatsApp
- E-mail
- Data e Horário
- Número de pessoas
- Observações

---

### 📍 Contato (Contact)

**Fale Conosco**
- 📞 (XX) XXXX-XXXX
- 💬 WhatsApp: (XX) XXXXX-XXXX
- ✉️ contato@restaurantepontobr.com.br
- 📍 [Endereço em Petrópolis ou local desejado]

**Horário de Funcionamento**
| Dia | Horário |
|---|---|
| Terça a Quinta | 11h30 – 15h30 / 18h – 23h |
| Sexta e Sábado | 11h30 – 23h30 |
| Domingo | 11h30 – 17h |

**Redes Sociais**
[Instagram (@restaurantepontobr)] · Facebook