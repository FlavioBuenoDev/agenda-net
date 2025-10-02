# 📝 Descrição da Tarefa
Explique claramente o que deve ser feito. Inclua o contexto do problema ou funcionalidade a ser desenvolvida.

---

# ✅ Critérios de Aceitação
- [ ] Liste os pontos que precisam ser cumpridos para considerar a tarefa concluída.
- [ ] O resultado esperado deve estar claro e objetivo.
- [ ] Sempre que possível, adicione exemplos.

---

# 🔧 Passos Técnicos (se aplicável)
1. Explique a ordem de implementação sugerida.
2. Detalhe comandos necessários ou dependências a instalar.
3. Indique arquivos/pastas onde o código deve ser alterado/criado.

---

# 📂 Exemplo de Código (opcional)
```python
# Exemplo para backend com FastAPI
from fastapi import FastAPI

app = FastAPI()

@app.get("/health")
def health():
    return {"status": "ok"}
