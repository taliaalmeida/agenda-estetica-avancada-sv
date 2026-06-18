# 🌸 Estética Avançada SV — Agenda Online

> Sistema completo de agendamento e gestão para clínica de estética, desenvolvido por **By Natalia Dev**

---

## ✨ Sobre o sistema

Sistema web completo com três perfis de acesso — Cliente, Profissional e Administrador — desenvolvido exclusivamente para a **Estética Avançada SV**. Sincronização em tempo real via Firebase, sem necessidade de instalar nada.

---

## 👤 Perfis de acesso

### 💁 Cliente
- Catálogo de serviços com preço e duração
- Agendamento online com escolha de profissional e horário
- Área pessoal com histórico de sessões
- Carteira de pacotes adquiridos
- Ficha de anamnese digital

### 🧑‍⚕️ Profissional
- Agenda individual com visão diária
- Prontuário eletrônico dos pacientes
- Registro de evolução clínica

### ⚙️ Administrador
- Visão geral com métricas do mês
- Agenda geral de todos os profissionais
- Cadastro de serviços com insumos vinculados
- Gestão da equipe com percentual de comissão
- Controle de salas e equipamentos
- Controle de estoque com baixa automática por procedimento
- Cálculo automático de comissões ao concluir atendimento
- Venda de pacotes de sessões
- Regras de negócio (horário, buffer entre clientes, dias de funcionamento)

---

## 🗂️ Organização por meses

Os dados ficam organizados automaticamente por mês — janeiro fica separado de fevereiro, sem misturar nada. A navegação entre meses é feita pelas setas ‹ › no cabeçalho.

---

## 🛠️ Tecnologias

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)

- HTML5, CSS3 e JavaScript puro — sem frameworks
- Firebase Realtime Database — sincronização em tempo real
- Hospedagem: GitHub Pages (gratuito)
- Fontes: Cormorant Garamond + DM Sans

---

## 📁 Estrutura do repositório

```
agenda-estetica-avancada-sv/
│
└── index.html     # Sistema completo em um único arquivo
└── README.md      # Este arquivo
```

---

## 🚀 Como hospedar

1. Faça upload do `index.html` no repositório do GitHub
2. Vá em **Settings → Pages**
3. Source: `main` → `/ (root)` → Save
4. Aguarde ~2 minutos e acesse o link gerado

---

## 🔥 Firebase

O sistema utiliza o projeto Firebase `caixa-clinicasv` já configurado. Os dados da agenda ficam separados do sistema de caixa:

| Sistema | Caminho no Firebase |
|---|---|
| Caixa da clínica | `meses/YYYY-MM/...` |
| Agenda | `agenda/YYYY-MM/...` e `agenda_global/...` |

---

## 📬 Desenvolvido por

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white)](https://wa.me/5521970189097)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://www.instagram.com/nataliaalmeidatech)

---

<p align="center">Desenvolvido com 🌸 por <strong>By Natalia Dev</strong></p>
