# Controle Leiteiro

Sistema de Gestao da Producao Leiteira - Projeto PSOO

## Problema

Dificuldade no controle e organizacao da producao de leite em propriedades rurais, especialmente no registro da ordenha realizada duas vezes ao dia, do rendimento de cada animal, alimentacao e saude do gado.

## Funcionalidades (12+)

1. **Login** - Autenticacao por telefone e PIN
2. **Cadastro de Produtor** - Registro do produtor e propriedade rural
3. **Dashboard** - Pagina inicial com resumo da producao
4. **Cadastro de Animais** - Gestao do rebanho leiteiro
5. **Registro de Ordenhas** - Ordenha manha e tarde
6. **Rendimento por Animal** - Produtividade individual
7. **Alimentacao** - Controle de racao do rebanho
8. **Saude do Rebanho** - Vacinas, tratamentos e exames
9. **Insumos** - Controle de estoque de racao e medicamentos
10. **Reproducao** - Coberturas e previsao de parto
11. **Relatorios** - Relatorios de producao leiteira
12. **Alertas** - Avisos de produtividade e saude
13. **Propriedade** - Dados da fazenda e funcionarios

## Tecnologias

- Python / Django 5.x
- SQLite
- HTML + CSS (sem Bootstrap)

## Como executar

```bash
cd controle-leiteiro
python -m venv venv
venv\Scripts\activate        # Windows
pip install django
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Acesse: http://127.0.0.1:8000/

- Frontend: http://127.0.0.1:8000/
- Admin: http://127.0.0.1:8000/admin/

## Estrutura

```
controle-leiteiro/
├── config/          # Configuracoes Django
├── app/
│   ├── models.py    # Entidades do sistema
│   ├── views.py     # Logica das paginas
│   ├── urls.py      # Rotas
│   ├── admin.py     # Painel administrativo
│   └── templates/   # Paginas HTML
├── manage.py
└── db.sqlite3
```

## Autor

Projeto academico PSOO - Controle Leiteiro
