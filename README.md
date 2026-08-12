# luanmotta.com.br

Site estático servido pelo GitHub Pages direto da branch `master` (sem build, sem Actions).
Separado de `luanmotta.github.io`, que serve **luanmotta.com** — o Pages aceita um domínio
custom por repo, então cada domínio tem o seu repo.

- `/intercambio-rotary/` — página de divulgação do Programa Jovem Destaque (Rotary D4670).
  **A fonte da verdade é `claude-life/rotary/site/index.html`**; aqui é cópia publicada por
  `claude-life/rotary/deploy.sh`. Não editar aqui.
- `/` — redireciona para `/intercambio-rotary/` enquanto não houver outra coisa no domínio.
- `CNAME` — o domínio custom. Não apagar; o Pages depende dele.
