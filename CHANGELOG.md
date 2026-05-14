# CHANGELOG — +Mais Placas

---

## 2026-05-13
- **Script:** corrigido replay da placa ao clicar — substituído `cloneNode` (quebrado) por restart via reflow (`animation = none → offsetWidth → animation = ''`)
- **UX:** cursor pointer e tooltip "Clique para girar a placa" adicionados à plate-scene
- **Seção impactada:** Script

---

## 2026-05-13
- **Animação da placa:** substituída `plate-rise` por `plate-spin` — 3 rotações 360° no eixo Y (0 → 1080deg), 1.8s, easing `cubic-bezier(0.15,0.5,0.3,1)`
- **CSS:** delay do `plate-snap` ajustado de 3.5s → 3.8s para sincronizar com a nova duração
- **Seção impactada:** CSS — `@keyframes plate-spin`, `.plate`

---

## 2026-05-13
- **Tema visual:** refatoração completa para identidade Mercosul / sinalização de trânsito
- **Paleta:** azul `#0052A5` (autoridade), amarelo `#F5C200` (sinalização), vermelho `#CC2200` (alerta)
- **Topbar:** fundo azul escuro, texto branco, badge "Aberto" amarelo
- **Hero:** faixa diagonal amarela (`clip-path`), 3 shapes geométricas flutuantes (barra amarela, círculo azul, barra vermelha)
- **Divisores:** signal stripe entre seções (faixas amarelas tracejadas, 4px)
- **Urgência:** CTA amarelo com texto escuro; restante dos CTAs em azul
- **Preço destaque:** borda e halo amarelo no card featured
- **Copy:** reposicionamento de autoridade — "Placa Mercosul em Bauru, hoje.", FAQ novo, urgência reescrita, sticky footer atualizado
- **Seção impactada:** CSS (tema completo), HTML (copy de todas as seções), Script (shapes + scroll reveal)

---

## 2026-05-13
- **Tema visual:** refatoração para nude sofisticado — paleta quente `#F7F0E8`, acento terracota `#B87040`
- **Motion:** grain overlay SVG, shapes flutuantes no hero, fadeUp por scroll (IntersectionObserver)
- **Hero:** fundo radial, tipografia 52px/66px, eyebrow com badge de autoridade
- **Seção impactada:** CSS (tema e motion), Script (shapes + scroll reveal)

---

## 2026-05-12
- **Tema:** fundo claro ativado, hero h1 aumentado de 42px → 52px (mobile) e 48px → 66px (desktop)
- **Seção impactada:** CSS

---

## 2026-05-12
- **Motion design:** topbar entrance, hero cascade, scroll progress bar, spotlight de mouse, card tilt 3D, parallax ambiente, contador de preço, stagger nos pain-steps
- **Seção impactada:** CSS, Script

---

## 2026-05-12
- **Projeto iniciado:** deploy no Railway via GitHub (`Matheusbenii/mais-placas`)
- `package.json`, `railway.json` e `.gitignore` criados
- Repositório inicializado e conectado ao Railway
