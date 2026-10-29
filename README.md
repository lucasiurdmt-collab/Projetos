# Sistema de Sorteio ao Vivo (vMix & Painel de LED) 🎉

Sistema profissional dividido em **Painel da Produção (Backstage)** e **Telão de Exibição (vMix / LED)** com estética baseada na **Caminhada do Amor / The Love Walk**.

---

## 🔗 Links Oficiais no GitHub Pages

1. **Painel da Produção (Equipe / Backstage):**
   👉 `https://lucasiurdmt-collab.github.io/Projetos/`
   - Onde a equipe carrega o Excel (.xlsx) ou CSV do Google Forms.
   - Opção para remover nomes duplicados.
   - Prévia dos participantes carregados.
   - Botão mestre: **"DISPARAR SORTEIO NO TELÃO!"**
   - Indicador de status em tempo real (mostra se o vMix/Telão está conectado).

2. **Telão de Exibição (vMix / Painel de LED):**
   👉 `https://lucasiurdmt-collab.github.io/Projetos/telao.html`
   - Visual limpo, cinematográfico, apenas o sorteio e animações.
   - Adicione no vMix como **Add Input > Web Browser**.
   - Dica: Adicione `?transparent=true` no final da URL (`telao.html?transparent=true`) se quiser usar como overlay sobre câmeras no vMix!

---

## ⚡ Como funciona a comunicação em tempo real
A comunicação entre o painel da equipe e o telão funciona **em tempo real** no navegador utilizando as APIs nativas `BroadcastChannel` e `localStorage`. Quando a equipe clica em **"Disparar Sorteio"**, o telão no vMix gira a roleta, toca o suspense e revela o vencedor com chuva de confetes e fanfarra!
