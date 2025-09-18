# 📊 Checklist de Trade — Risco x Retorno (RR)

Ferramenta simples em **HTML + JS** para calcular rapidamente a **relação Risco x Retorno (RR)** antes de abrir qualquer trade.

---

## 🚀 Como acessar

Acesse pelo GitHub Pages:  
👉 [Abrir Checklist de Trade](https://alexandrerela2.github.io/regrarrtrade/)

*(Se não abrir de primeira, verifique nas configurações do repositório se o **Pages** está habilitado em `Settings → Pages → Source: main branch / root` e aguarde alguns minutos para atualizar.)*

---

## 📋 Como usar
1. Escolha **Direção** (Long ou Short).  
2. Preencha **Entrada**, **Stop** e pelo menos um **Alvo**.  
3. Informe sua **banca** e o **% de risco por trade**.  
4. A tabela calcula automaticamente:
   - Distância até o Stop (**Risco**)  
   - Distância até cada Alvo (**Retorno**)  
   - **RR (Retorno ÷ Risco)**  
   - **Tamanho da posição** (unidades)  
   - **P/L estimado**  
   - **RR ponderado** em caso de saídas parciais  

O selo fica **verde** quando o trade tem **RR ≥ mínimo configurado** (por padrão 2:1).

---

## 🛠️ Como alterar
- O código está no arquivo [`index.html`](./index.html).  
- Abra em qualquer editor de texto (ex.: **VS Code**).  
- Principais pontos editáveis:
  - Placeholders (valores de exemplo nos inputs)  
  - Cores do tema (variáveis no `<style>`)  
  - RR mínimo (padrão 2.0, configurável na interface)  
  - Saídas parciais (% por alvo)  

---

## 📱 Dica para celular
- Abra o link no navegador do celular.  
- Menu → **Adicionar à tela inicial** → vira um “appzinho” offline.  

---

## 📂 Estrutura do projeto

