# Projetos CGINT

Coleção de ferramentas e visualizações para análise e gestão.

## 🚀 Acesso

Acesse o site: [https://Alexandre1BR.github.io/Projetos-CGINT](https://SEU-USUARIO.github.io/Projetos-CGINT)

## 📂 Projetos Incluídos

### 1. Calculadora de Renda Fixa
Ferramenta completa para comparação de investimentos em renda fixa:
- **CDB** (Certificado de Depósito Bancário)
- **LCI/LCA** (Letras de Crédito Imobiliário/Agronegócio)
- **Tesouro SELIC**
- **Tesouro IPCA+**

**Funcionalidades:**
- Comparação de cenários de curto, médio e longo prazo
- Simulação de reinvestimento automático
- Cálculo de come-cotas (fundos de investimento)
- Simulação de cupom semestral
- Gráficos e tabelas comparativas

### 2. Diagrama de Governança de APIs
Visualização interativa que demonstra:
- Comparação entre API única vs. múltiplas APIs segregadas
- Impacto de incidentes de segurança em diferentes arquiteturas
- Cenários de bloqueio e contenção
- Modelo de governança SSP/SC ↔ MJSP (Plataforma Córtex)

## 🛠️ Tecnologias

- **HTML5** - Estrutura
- **CSS3** - Estilização com variáveis CSS
- **JavaScript (Vanilla)** - Lógica da calculadora
- **React (CDN)** - Interface do diagrama
- **Tailwind CSS (CDN)** - Estilização do diagrama

## 📦 Como Hospedar no GitHub Pages

### Passo 1: Criar Repositório
```bash
# Inicializar o repositório (se ainda não foi feito)
git init

# Adicionar todos os arquivos
git add .

# Fazer o primeiro commit
git commit -m "Adiciona projetos CGINT: calculadora e diagrama de APIs"

# Criar repositório no GitHub e conectar
git remote add origin https://github.com/SEU-USUARIO/Projetos-CGINT.git

# Enviar para o GitHub
git push -u origin master
```

### Passo 2: Ativar GitHub Pages
1. Acesse o repositório no GitHub
2. Vá em **Settings** (Configurações)
3. No menu lateral, clique em **Pages**
4. Em **Source**, selecione a branch `master` (ou `main`)
5. Selecione a pasta `/ (root)`
6. Clique em **Save**

Aguarde alguns minutos e seu site estará disponível em:
`https://SEU-USUARIO.github.io/Projetos-CGINT`

## 📝 Estrutura do Projeto

```
Projetos CGINT/
├── index.html                      # Página inicial
├── README.md                       # Este arquivo
├── .gitignore                      # Arquivos ignorados pelo Git
├── assets/                         # Recursos estáticos
│   └── images/                     # Imagens e logos
│       ├── logo-cgint.png          # Logo CGINT
│       └── logo-republica.png      # Logo República
└── projetos/                       # Projetos individuais
    ├── calculadora-renda-fixa.html # Calculadora de investimentos
    └── governanca-apis.html        # Diagrama de governança de APIs
```

## 🎯 Uso Local

Para testar localmente, basta abrir o arquivo `index.html` em qualquer navegador moderno:

1. Navegue até a pasta do projeto
2. Clique duas vezes no arquivo `index.html`
3. OU use um servidor local (recomendado):
   ```bash
   # Python 3
   python -m http.server 8000

   # Acesse: http://localhost:8000
   ```

## ⚠️ Avisos Importantes

- **Calculadora de Renda Fixa**: Os cálculos são aproximações para fins educacionais. Consulte um assessor de investimentos para decisões financeiras reais.
- **Diagrama de APIs**: Modelo conceitual para fins de apresentação e análise técnica.

## 📄 Licença

Desenvolvido para fins educacionais e análise técnica.

---

**CGINT** - Coordenação-Geral de Inteligência
