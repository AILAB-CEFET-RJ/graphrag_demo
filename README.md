
# GraphRAG Demo

Este projeto implementa uma pipeline de Graph-RAG (Graph-based Retrieval-Augmented Generation), que integra modelos de linguagem natural com técnicas de recuperação de informações em grafos. Ele permite realizar tarefas como pergunta e resposta, resumos, entre outras, utilizando dados contextuais e indexados.



## Configuração do Ambiente

**1. Clone o repositório**

```bash
  git clone https://github.com/AILAB-CEFET-RJ/graphrag_demo.git
  cd graphrag_demo
```

**2. Configure e ative o ambiente virtual**

No Windows:
```bash
  python -m venv venv
  venv\Scripts\activate
```

No Linux/macOS:
```bash
  python3 -m venv venv
  source venv/bin/activate
```

**3. Instale as dependências**

```bash
  pip install -r requirements.txt
```

## Como Executar

Para executar os notebooks basta rodar o comando:

```bash
  jupyter notebook nome-do-notebook.ipynb
```

Para extrair as entidade e relacionamentos, use os prompts encontrados nos arquivos, no ChatGPT. Para facilitar essa extração, transforme o PDF de entrada em um arquivo .txt e remova o sumário e outras partes sem conteúdo. 



## Próximos Passos
**1.** Avaliar modelos com mais parâmetros:

Testar outros modelos de linguagem com maior capacidade e número de parâmetros para potencialmente melhorar a qualidade das respostas e a performance geral do agente.

**2.** Refinar o prompt de extração:

Aprimorar o prompt responsável pela extração de entidades e relacionamentos no documento de entrada, garantindo resultados mais precisos e relevantes para alimentar o pipeline de Graph-RAG.

**3.** Integrar com a OpenAI e GraphRAG:

Integrar a API da OpenAI com o [GraphRAG](https://github.com/microsoft/graphrag) para aproveitar as vantagens da recuperação aumentada com grafos e melhorar a geração de respostas baseadas em contexto.
## Referências

- [Exemplo GraphRAG](https://www.youtube.com/watch?v=6vG_amAshTk&t=339s)
- [Documentação Pytorch](https://docs.pytorch.org/docs/stable/index.html)
- [Documentação Networkx](https://networkx.org/documentation/stable/tutorial.html)
- [Tiny Llama](https://ollama.com/library/tinyllama)

