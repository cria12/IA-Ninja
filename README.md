````markdown
# IA Ninja — Curso de IA + Automação com n8n

> "Domine Inteligência Artificial e torne-se um IA Ninja"  
> Crie fluxos inteligentes, automatize processos e forme um verdadeiro **exército de agentes** com **n8n + IA**.

---

## 🎯 Visão Geral

Este repositório é o hub oficial de materiais que acompanham o curso **IA Ninja**.  
Aqui você encontra **exemplos práticos, templates de automação, projetos guiados** e material complementar exclusivo, incluindo um e-book completo sobre **JSON**.

🔗 **Links oficiais:**
- 🌐 [Landing Page do Curso](https://novo-primeiro-app-2026.vercel.app/)  
- 🎓 [Página do Curso no Hotmart](https://hotmart.com/pt-br/marketplace/produtos/n8n-na-pratica-do-zero-a-criacao-de-um-exercito-de-agentes/S101896205J)  
- 📖 [E-book Estrutura do JSON (download)](./ebook%20json.pdf)  

---

## 🧩 O que você vai aprender

- Fundamentos do **n8n**: instalação, nodes, triggers e fluxos.  
- Como integrar **IA generativa** (ChatGPT, Gemini e outros modelos).  
- Criação de **agentes inteligentes** e fluxos multiagentes.  
- Uso do **JSON** como cola universal de APIs e dados.  
- Melhores práticas, casos reais e deploy de workflows em produção.  
- Bônus: **E-book JSON** — guia definitivo para estruturar, validar e otimizar dados.  

---

## 📚 Conteúdo do Curso

1. Introdução ao n8n e visão geral  
2. Manipulação de dados (JSON e APIs)  
3. Primeira automação prática  
4. Conexão com IA e engenharia de prompts  
5. Criação de agentes inteligentes  
6. Multiagentes e escalabilidade  
7. Deploy e monitoramento  
8. Projetos finais + templates prontos  
9. **Material extra: E-book Estrutura do JSON**  

---

## 📖 E-book Exclusivo

Além do curso, você recebe acesso ao **E-book Estrutura do JSON**, cobrindo:  
- Sintaxe, padrões e validação (JSON Schema)  
- Casos reais de uso em APIs, logs, configs  
- Boas práticas e armadilhas comuns  
- Ferramentas, variantes e performance  
- Checklist final para garantir JSON perfeito  

👉 [Baixe o e-book aqui](./ebook%20json.pdf)

---

## 🛠 Instalação / Setup

Clone este repositório e explore os exemplos:

```bash
git clone https://github.com/seu-usuario/ia-ninja.git
cd ia-ninja
````

Se houver módulos Node.js:

```bash
npm install
npm run dev
```

Ou com Docker:

```bash
docker-compose up --build
```

---

## 🚀 Exemplos Rápidos

### Workflow simples no n8n:

* HTTP Trigger → Node de IA → Node condicional → Node de saída

### Trecho em Node.js:

```js
const { runAgent } = require('./modules/agent');

(async () => {
  const resposta = await runAgent({
    prompt: "Explique JSON em 3 frases",
    context: { curso: "IA Ninja" }
  });
  console.log(resposta);
})();
```

---

## 🤝 Contribuição

Quer ajudar?

1. Faça **fork**
2. Crie sua branch (`feature/novo-agent`)
3. Commit claro e objetivo
4. Abra um PR

---

## 📜 Licença

Este projeto está licenciado sob **MIT License**.
Você pode usar, modificar e distribuir, mantendo os créditos.

---

## 👤 Autor

Criado por **Davi Silva**.
Especialista em IA, Metaverso e Web3.0.

* 🌐 [Landing Page](https://novo-primeiro-app-2026.vercel.app/)
* 📖 [E-book Estrutura do JSON](./ebook%20json.pdf)
* 🎓 [Curso no Hotmart](https://hotmart.com/pt-br/marketplace/produtos/n8n-na-pratica-do-zero-a-criacao-de-um-exercito-de-agentes/S101896205J)

---

```
```

![imagem criador curso ](https://static-media.hotmart.com/RPihVLrikOvc1OM1XgrgQoWktYY=/140x140/smart/filters:format(webp):background_color(white)/hotmart/product_contents/1f61d295-83bf-414f-ae1d-816cc1bc1930/543687897_18529913890026811_7803773789856421059_n.jpg?w=920)
