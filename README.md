# 🌿 EcoPonto Condomínio — Guia de Reciclagem e Descarte Sustentável

> Aplicação Web *mobile-first* desenvolvida como Projeto de Extensão Universitária em Engenharia de Computação, focada na conscientização ambiental, gestão eficiente de resíduos e alinhamento com o **ODS 13 da ONU (Ação Contra a Mudança Global do Clima)** no município de Ubatuba/SP.

---

## 🎯 Sobre o Projeto

O **EcoPonto Condomínio** foi projetado para resolver falhas de comunicação interna em condomínios residenciais em relação à separação e destino correto do lixo. A aplicação é acessada diretamente pelos moradores via **QR Code** afixado nos elevadores e áreas comuns, fornecendo informações instantâneas sobre regras de descarte e localização dos pontos de recolha.

### 🚀 Funcionalidades Principais

- **🔍 Onde Descartar?:** Mecanismo de busca rápida para dezenas de itens do dia a dia (PET, óleo de cozinha, pilhas, vidro, embalagens Tetra Pak, etc.) indicando as cores oficiais (padrão CONAMA) e orientações de higienização.
- **📍 Mapeamento dos Ecopontos:** Guia visual dos pontos de coleta internos do condomínio (Central, Garagem, Composteira, etc.).
- **🧮 Calculadora de Impacto Ambiental:** Estimativa em tempo real de CO₂ evitado, água poupada e árvores preservadas com base na reciclagem semanal.
- **🗓️ Coleta Seletiva em Ubatuba:** Informações integradas sobre o cronograma municipal de coleta e pontos de entrega voluntária (PEV).
- **📢 Central de Reportes:** Formulário simples para moradores notificarem a administração sobre lixeiras cheias ou irregularidades.

---

## 🛠️ Tecnologias Utilizadas

- **Backend:** Python 3 + FastAPI
- **Templating Engine:** Jinja2
- **Frontend:** HTML5, CSS3 (Tailwind CSS) e JavaScript (Vanilla)
- **Servidor ASGI:** Uvicorn

---

## 📁 Estrutura do Projeto

```text
.
├── main.py                # Servidor FastAPI e rotas da aplicação
├── templates/
│   └── index.html         # Interface web mobile-first
└── README.md              # Documentação do repositório
