# Tempero Caseiro — Site Flask

## Rodar localmente

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/macOS
source venv/bin/activate

pip install -r requirements.txt
python app.py
```

Abra: http://127.0.0.1:5000

## Estrutura
- `app.py`: aplicação Flask
- `templates/index.html`: página principal
- `static/css/style.css`: identidade visual e responsividade
- `static/js/script.js`: menu mobile e animações
- `static/img/`: imagens tratadas/compostas do projeto
- `vercel.json`: configuração opcional para deploy na Vercel
