# Projetos CGINT - Repositório de Testes

**AVISO IMPORTANTE:** Este repositório contém sistemas de **teste e demonstração** desenvolvidos exclusivamente para fins educacionais e experimentação com tecnologias web. **NÃO possui qualquer relação oficial** com a Coordenação-Geral de Inteligência (CGINT), Diretoria de Operações Integradas e de Inteligência (DIOPI), Secretaria Nacional de Segurança Pública (SENASP) ou Ministério da Justiça e Segurança Pública (MJSP).

A identidade visual utilizada foi criada como template de teste para simular a aparência de portais governamentais, servindo exclusivamente como ambiente de desenvolvimento e aprendizado de tecnologias front-end.

## 🎯 Objetivo

Este repositório foi criado para:
- Teste de HTML5 e CSS3 moderno
- Experimentação com JavaScript vanilla e React
- Desenvolvimento de interfaces responsivas
- Prática de design de sistemas web
- Testes de deploy em GitHub Pages

## 🚀 Acesso ao Ambiente de Testes

Ambiente de demonstração: [https://Alexandre1BR.github.io/Projetos-CGINT](https://Alexandre1BR.github.io/Projetos-CGINT)

## 📂 Projetos de Demonstração

### 1. Calculadora de Renda Fixa
Sistema de teste para análise comparativa de investimentos em renda fixa:
- **CDB** (Certificado de Depósito Bancário)
- **LCI/LCA** (Letras de Crédito Imobiliário/Agronegócio)
- **Tesouro SELIC**
- **Tesouro IPCA+**

**Funcionalidades implementadas:**
- Comparação de cenários de curto, médio e longo prazo
- Simulação de reinvestimento automático
- Cálculo de come-cotas (fundos de investimento)
- Simulação de cupom semestral
- Gráficos e tabelas comparativas interativas

**Nota:** Os cálculos são aproximações para fins educacionais. Para decisões financeiras reais, consulte um assessor de investimentos credenciado.

### 2. Diagrama de Governança de APIs
Ferramenta de visualização interativa que demonstra:
- Comparação entre gestão centralizada vs. descentralizada de APIs
- Impacto de diferentes arquiteturas de controle de acesso
- Cenários de bloqueio e contenção em situações hipotéticas
- Modelo de governança aplicável a Secretarias de Segurança Pública

**Objetivo técnico:** Demonstrar conceitos de arquitetura de APIs, segregação de acessos e resiliência operacional através de visualização interativa.

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização com variáveis CSS e Flexbox/Grid
- **JavaScript (ES6+)** - Lógica e interatividade
- **React 18** - Componentes interativos (via CDN)
- **Tailwind CSS** - Framework CSS utilitário (via CDN)

Todos os recursos são carregados via CDN, sem necessidade de build ou dependências locais.

## 📝 Estrutura do Repositório

```
Projetos-CGINT/
├── index.html                      # Página inicial de navegação
├── README.md                       # Este arquivo
├── .gitignore                      # Arquivos ignorados pelo Git
├── assets/                         # Recursos estáticos
│   └── images/                     # Imagens e logos de teste
│       ├── logo-cgint.png          # Logo usado como exemplo visual
│       └── logo-republica.png      # Logo usado como exemplo visual
└── projetos/                       # Projetos de demonstração
    ├── index.html                  # Listagem de projetos
    ├── calculadora-renda-fixa.html # Calculadora de investimentos
    └── governanca-apis.html        # Diagrama de governança de APIs
```

## 🎯 Como Usar Localmente

### Opção 1: Abrir diretamente no navegador
1. Clone o repositório
2. Abra o arquivo `index.html` no navegador

### Opção 2: Servidor local (recomendado)
```bash
# Clone o repositório
git clone https://github.com/Alexandre1BR/Projetos-CGINT.git
cd Projetos-CGINT

# Inicie um servidor HTTP local
# Python 3
python -m http.server 8000

# Ou use qualquer outro servidor local de sua preferência
# Acesse: http://localhost:8000
```

## 📦 Deploy no GitHub Pages

Este repositório está configurado para deploy automático via GitHub Pages:

1. Repositório público no GitHub
2. Settings → Pages → Source: `master` branch, pasta `/ (root)`
3. O site é publicado automaticamente em: `https://USERNAME.github.io/REPO-NAME`

## ⚠️ Avisos e Disclaimers

### Sobre o Conteúdo
- **Não oficial:** Este projeto não tem qualquer vínculo oficial com órgãos governamentais
- **Fins educacionais:** Todo conteúdo é para aprendizado e experimentação técnica
- **Dados fictícios:** Todas as informações e cenários são hipotéticos
- **Sem garantias:** Os cálculos e simulações não devem ser usados para decisões reais

### Sobre a Identidade Visual
- O template visual foi criado **exclusivamente para testes** de desenvolvimento web
- A semelhança com identidades governamentais é **apenas para fins de estudo** de padrões de design
- Não representa, endossa ou tem autorização de qualquer órgão público

### Calculadora de Renda Fixa
- Os cálculos são aproximações e podem conter imprecisões
- Não substitui orientação profissional de investimentos
- Consulte instituições financeiras e assessores credenciados para decisões reais

### Diagrama de Governança
- Cenários puramente hipotéticos e educacionais
- Não reflete arquiteturas reais de qualquer organização
- Desenvolvido para estudo de conceitos técnicos de arquitetura de software

## 🔧 Desenvolvimento

### Tecnologias de Front-end
- HTML5 semântico
- CSS3 moderno (variáveis CSS, Grid, Flexbox)
- JavaScript ES6+ (classes, arrow functions, modules)
- React 18 (componentes funcionais, hooks)

### Padrões de Código
- Responsividade mobile-first
- Acessibilidade (ARIA labels, navegação por teclado)
- Performance (lazy loading, código otimizado)
- Compatibilidade cross-browser

## 📄 Licença e Uso

Este projeto está disponível publicamente no GitHub para fins educacionais.

**Termos de uso:**
- Livre para estudo e aprendizado
- Não deve ser usado para representar órgãos oficiais
- Não possui garantias de funcionamento
- O desenvolvedor não se responsabiliza por uso indevido

## 🤝 Contribuições

Este é um projeto pessoal de estudos. Sugestões e melhorias são bem-vindas através de issues no GitHub.

---

**Desenvolvido como projeto de testes e aprendizado de tecnologias web**
Ambiente de demonstração disponível em: https://Alexandre1BR.github.io/Projetos-CGINT
