# +Mais Placas — Instruções de Projeto

## Stack
- Site estático HTML/CSS/JS único (`index.html`)
- Deploy: Railway (auto-deploy via push no GitHub → `Matheusbenii/mais-placas`)
- Serve: `npx serve -s . -l $PORT`

## Workflow obrigatório ao final de TODA tarefa

Ao terminar qualquer alteração, execute SEMPRE nesta ordem:

### 1. Commit com mensagem descritiva
```bash
git add index.html
git commit -m "descrição clara do que foi feito"
```

### 2. Push para o GitHub (dispara deploy no Railway)
```bash
git push origin master
```

### 3. Atualizar o CHANGELOG.md
Adicione uma entrada no topo do arquivo `CHANGELOG.md` com:
- Data (formato `YYYY-MM-DD`)
- O que foi alterado (bullet points objetivos)
- Seção impactada (CSS / HTML / Script)

Exemplo de entrada:
```markdown
## 2026-05-13
- **Animação da placa:** substituída `plate-rise` por `plate-spin` (3 rotações 360° eixo Y, 1.8s)
- **CSS:** ajustado delay do `plate-snap` de 3.5s → 3.8s
```

## Regras fixas
- **Nunca alterar** os atributos `href` dos links WhatsApp
- Sempre testar visualmente no preview antes de commitar
- Commit deve ter mensagem em português, clara e específica
