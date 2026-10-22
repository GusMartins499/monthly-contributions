# Contribuições do mês

Veja o gráfico de contribuições de qualquer usuário do GitHub em um mês específico, no estilo do calendário do perfil.

**Acesse:** https://gusmartins499.github.io/month-commits-graph-gh/

- Calendário do mês com os níveis de cor do GitHub (tema claro e escuro)
- Total de contribuições, dias ativos, maior sequência e melhor dia
- Navegação entre meses e link compartilhável (`?user=<login>&mes=AAAA-MM`)

Página estática em um único `index.html`, sem build. Os dados vêm da
[github-contributions-api](https://github.com/grubersjoe/github-contributions-api).

## Rodando localmente

```bash
python3 -m http.server 8000
```

Depois abra http://localhost:8000.
