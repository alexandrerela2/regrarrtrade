# 📊 Checklist de Trade — Risco x Retorno (RR)

Este projeto é uma ferramenta simples em **HTML + JS** para calcular rapidamente a **relação Risco x Retorno (RR)** antes de abrir qualquer trade.

---

## 🚀 Como acessar

A página está publicada no **GitHub Pages**:  
👉 [Abrir Checklist de Trade](https://alexandrerela2.github.io/regrarrtrade/)

*(Se ainda não abriu, aguarde alguns minutos após ativar o Pages nas configurações do repositório)*

---

## 📋 Como usar
1. Abra o link no navegador.  
2. Escolha **Direção** (Long ou Short).  
3. Preencha **Entrada**, **Stop** e pelo menos 1 **Alvo**.  
4. A tabela calcula automaticamente:
   - Distância até o Stop (**Risco**)  
   - Distância até o Alvo (**Retorno**)  
   - **RR (Retorno ÷ Risco)**  
5. O selo fica **verde** quando o trade tem **RR ≥ 2:1**.

---

## 🛠️ Como alterar
- O código está no arquivo [`index.html`](./index.html).  
- Abra em qualquer editor de texto (ex.: **VS Code**).  
- Principais pontos editáveis:
  - Placeholders (valores de exemplo nos inputs)  
  - Cores do tema (no bloco `:root` dentro do `<style>`)  
  - Regra mínima de RR (no script: `rr>=2`)  

---

## 📱 Dica para celular
- Abra o link no navegador do celular.  
- Menu → **Adicionar à tela inicial** → vira um “appzinho” offline.  

---

## 📂 Estrutura do projeto
