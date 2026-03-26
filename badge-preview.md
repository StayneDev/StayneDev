# Badge Preview — Visitor Counter Variations

> Comparativo das estratégias e variações de cor. Escolha uma e aplicamos no README principal.

---

## Estratégia A — komarev.com/ghpvc
Controla: fundo do label + fundo do contador. Texto automático (preto em fundo claro, branco em fundo escuro).

### A1 — Verde label / Preto count ← atual
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=StayneDev&style=for-the-badge&label=VISITORS&color=0d0d0d&labelColor=00ff41"/>
</p>

```
labelColor=00ff41  color=0d0d0d
Texto label: preto automático (contraste alto ✅)
Texto count: branco automático (contraste alto ✅)
```

---

### A2 — Preto label / Verde count
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=StayneDev&style=for-the-badge&label=VISITORS&color=00ff41&labelColor=0d0d0d"/>
</p>

```
labelColor=0d0d0d  color=00ff41
Texto label: branco automático (contraste alto ✅)
Texto count: preto automático (contraste alto ✅)
```

---

### A3 — Cinza grafite label / Verde escuro count
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=StayneDev&style=for-the-badge&label=VISITORS&color=003b00&labelColor=1a1a1a"/>
</p>

```
labelColor=1a1a1a  color=003b00
Texto label: branco automático (contraste alto ✅)
Texto count: branco automático (contraste médio ⚠️ — verde escuro)
Estética mais sutil / terminal vintage
```

---

## Estratégia B — hits.seeyoufarm.com
Controla: fundo do label, fundo do contador, cor do ícone. Contador por URL visitada — contagem independente do komarev.

### B1 — Preto label / Verde count + ícone terminal
<p align="center">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FStayneDev&count_bg=%2300FF41&title_bg=%230d0d0d&icon=terminal&icon_color=%2300ff41&title=VISITORS&edge_flat=true"/>
</p>

```
title_bg=#0d0d0d  count_bg=#00ff41  icon=terminal  icon_color=#00ff41
Texto label: branco automático ✅
Texto count: preto automático ✅
```

---

### B2 — Verde label / Preto count + ícone github
<p align="center">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FStayneDev&count_bg=%230d0d0d&title_bg=%2300ff41&icon=github&icon_color=%230d0d0d&title=VISITORS&edge_flat=true"/>
</p>

```
title_bg=#00ff41  count_bg=#0d0d0d  icon=github  icon_color=#0d0d0d
Texto label: preto automático ✅
Texto count: branco automático ✅
```

---

### B3 — Azul escuro label / Ciano count (paleta alternativa ao matrix)
<p align="center">
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FStayneDev&count_bg=%2300b4d8&title_bg=%230d1b2a&icon=terminal&icon_color=%2300b4d8&title=VISITORS&edge_flat=true"/>
</p>

```
title_bg=#0d1b2a  count_bg=#00b4d8  icon=terminal  icon_color=#00b4d8
Paleta diferente — ciano/navy. Saída do tema matrix, mais clean.
Texto label: branco automático ✅
Texto count: preto automático ✅
```

---

## Resumo

| Versão | Estratégia | Label bg | Count bg | Ícone | Diferencial |
|:---:|---|---|---|---|---|
| A1 | komarev | `#00ff41` verde | `#0d0d0d` preto | — | ← atual |
| A2 | komarev | `#0d0d0d` preto | `#00ff41` verde | — | invertido |
| A3 | komarev | `#1a1a1a` grafite | `#003b00` verde escuro | — | sutil |
| B1 | hits | `#0d0d0d` preto | `#00ff41` verde | terminal verde | com ícone |
| B2 | hits | `#00ff41` verde | `#0d0d0d` preto | github preto | com ícone |
| B3 | hits | `#0d1b2a` navy | `#00b4d8` ciano | terminal ciano | paleta alternativa |

Diga qual prefere (ex: "B1") e aplico no README.
