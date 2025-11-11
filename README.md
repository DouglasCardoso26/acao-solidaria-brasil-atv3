# 🌍 Ação Solidária Brasil — Atividade 3

## 🎯 Objetivo
Esta terceira entrega tem como foco a **implementação de JavaScript avançado** para transformar a interface estática do site da ONG *Ação Solidária Brasil* em uma aplicação web dinâmica e interativa.  
Foram aplicados conceitos de **manipulação do DOM**, **eventos**, **armazenamento local**, **Single Page Application (SPA)** e **organização modular do código**.

---

## 🧱 Estrutura da Entrega

<pre>
acao-solidaria-brasil/
├── index.html
├── projetos.html
├── cadastro.html
│
├── css/
│   └── style.css
│
├── js/
│   ├── router.js
│   ├── form.js
│   ├── menu.js
│   ├── masks.js
│   └── templates.js
│
└── assets/
    └── media/
</pre>

---

## ⚙️ Funcionalidades Implementadas

### 🧭 Sistema SPA (Single Page Application)
- As páginas **Início**, **Projetos** e **Cadastro** são carregadas dinamicamente via `router.js`.  
- O SPA utiliza **hash routing** (`#/projetos`, `#/cadastro`) e mantém o **estado ativo do menu**.  
- Quando o site é aberto localmente (`file://`), o sistema automaticamente volta ao modo tradicional (sem erros).

### 🧩 Sistema de Templates JavaScript
- `templates.js` fornece funções para criar elementos dinâmicos, como:
  ```js
  Templates.alert('success', 'Cadastro realizado com sucesso!');
Permite personalizar mensagens e avisos diretamente pelo JavaScript.

🧾 Validação de Formulários

Implementada em form.js, com:

Verificação real de CPF (dígitos verificadores);

Validação de idade mínima (16 anos);

Mensagens visuais de sucesso e erro;

Armazenamento do nome do último cadastro no localStorage.

📱 Menu Responsivo

Cabeçalho fixo com menu hambúrguer para telas pequenas;

Fecha ao clicar fora ou pressionar ESC;

Destaca a página atual com sublinhado verde institucional.

🎨 Estilo e Acessibilidade

Cores e tipografia coerentes com o tema da ONG;

Foco visível em todos os elementos interativos;

Link “Pular para o conteúdo” para acessibilidade de teclado;

Imagens com loading="lazy" e proporções fixas;


💚 Sobre o Projeto

A Ação Solidária Brasil é uma ONG fictícia criada para fins acadêmicos.
Atua em três pilares principais:

Pilar	Descrição
🥗 Segurança Alimentar	Distribuição de cestas básicas e hortas comunitárias
📚 Educação e Oficinas	Apoio escolar e oficinas profissionais
💻 Inclusão Digital	Capacitação tecnológica e oportunidades de primeiro emprego

👨‍💻 Autor

Douglas Cardoso

Desenvolvimento Web 

📅 Atividade 3 — Implementação de JavaScript Avançado
