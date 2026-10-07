# agent-clt-escravo
# 🚀 Configuração de LLMs para VS Code + Continue

Este projeto traz uma configuração **balanceada e otimizada** para usar modelos de linguagem (LLMs) via [OpenRouter](https://openrouter.ai) dentro do **VS Code** com a extensão [Continue](https://continue.dev).  
O objetivo é oferecer **custo-benefício top**: rodar modelos baratos para tarefas simples e reservar os modelos mais caros e poderosos para momentos críticos.

---

## 📦 Sobre a extensão Continue
O [Continue](https://continue.dev) é uma extensão para VS Code que integra LLMs diretamente no fluxo de desenvolvimento.  
Com ele você pode:
- Gerar commits automaticamente (`/commit`)
- Criar documentação técnica (`/docs`)
- Revisar código (`/review`)
- Gerar testes unitários (`/test`)
- Refatorar código (`/refactor`)
- Criar APIs Node.js (`/api`)
- Criar componentes React (`/react`)
- Gerar SQL otimizado (`/sql`)

Tudo isso sem sair do editor, usando diferentes modelos conforme a necessidade.

---

## ⚙️ Configuração YAML
A configuração está organizada por **área e nível** (junior, pleno, senior).  
Isso permite escolher o modelo certo para cada tarefa, equilibrando **qualidade** e **custo**.

### 🎨 Frontend
- **Junior** → Microsoft Phi‑3 Vision Pro *(barato e rápido, ideal para UI simples)*  
- **Pleno** → OpenAI GPT‑5.6 Terra Pro *(equilibrado, gera código sólido)*  
- **Senior** → OpenAI GPT‑6.1 Sol *(top de linha, refatorações complexas)*  

### ⚙️ Backend
- **Junior** → DeepSeek V4 Pro *(custo acessível, lógica básica)*  
- **Pleno** → OpenAI GPT‑5.6 Terra Pro *(confiável para APIs)*  
- **Pleno (alternativa)** → Meta LLaMA 3.1 405B *(bom equilíbrio custo/performance)*  
- **Senior** → OpenAI GPT‑6 Astra Pro *(excelente para arquiteturas complexas)*  
- **Senior (alternativa)** → Anthropic Claude 3.5 Sonnet *(forte em raciocínio e documentação)*  

### 🏗️ Arquitetura
- **Pleno** → Meta LLaMA 3.1 405B *(bom para estruturar sistemas e boas práticas)*  
- **Senior** → Anthropic Claude 3.5 Sonnet *(raciocínio profundo, decisões arquiteturais)*  
- **Senior (alternativa)** → OpenAI GPT‑6.1 Sol *(soluções avançadas e detalhadas)*  

---

## 💰 Custo-benefício
- **Modelos Junior/Pleno** → baratos, ideais para uso diário dentro do orçamento de ~US$ 3/semana.  
- **Modelos Senior** → caros, mas reservados para tarefas críticas onde a qualidade máxima compensa o custo.  

👉 Assim você consegue rodar bastante coisa sem estourar o orçamento, mas ainda tem acesso aos melhores modelos quando precisar.

---

## 📋 Como usar
1. Instale o [VS Code](https://code.visualstudio.com/) e a extensão [Continue](https://marketplace.visualstudio.com/items?itemName=Continue.continue).
2. Configure sua chave do [OpenRouter](https://openrouter.ai).
3. Substitua `xxxxxx` no arquivo YAML pela sua chave.
4. Escolha o modelo conforme a necessidade (junior, pleno ou senior).

---

## 🏆 Conclusão
Essa configuração oferece:
- **Flexibilidade** → diferentes modelos para diferentes níveis de complexidade.  
- **Eficiência** → uso inteligente dos créditos semanais.  
- **Qualidade** → acesso a modelos de ponta quando necessário.  

Com isso, você terá um ambiente de desenvolvimento **mais produtivo, inteligente e econômico**.
