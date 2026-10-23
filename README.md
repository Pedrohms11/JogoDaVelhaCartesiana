# 🎮 Jogo da Velha Cartesiano

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> 🎓 Uma ferramenta educacional interativa que une o clássico Jogo da Velha com o aprendizado do Plano Cartesiano e conceitos de robótica.

---

## 📖 Sobre o Projeto

Este é um **Jogo da Velha Cartesiano** desenvolvido para ensinar coordenadas, quadrantes e lógica de programação de forma lúdica. O jogo desafia o aluno a **digitar coordenadas (x, y)** para fazer suas jogadas, com um sistema progressivo que libera o uso do mouse apenas após **3 vitórias** contra o computador.

O projeto foi pensado para o **ensino técnico em robótica e desenvolvimento de sistemas**, conectando conceitos matemáticos com aplicações práticas.

### 🎯 Público-alvo
- Estudantes do Ensino Médio e Técnico
- Cursos de Desenvolvimento de Sistemas
- Entusiastas de robótica e programação
- Professores que buscam material didático interativo

---

## ✨ Funcionalidades

### 🕹️ **Modo Aprendizagem**
- O jogador **digita as coordenadas** (x, y) para jogar
- O clique no canvas fica **bloqueado** até que o aluno prove que sabe usar coordenadas
- Feedback visual em tempo real

### 🏆 **Sistema de Progressão**
- **3 vitórias** contra o computador liberam o **clique no canvas**
- Estrelas ⭐ indicam o progresso de vitórias
- Ao vencer, o sistema sorteia um **novo quadrante** para jogar

### 🤖 **Computador Inteligente**
- **Nível Fácil:** Escolhe posições aleatórias
- **Nível Médio:** Tenta vencer e bloquear o adversário
- **Nível Difícil:** Usa estratégia avançada (Minimax simplificado)

### 🔐 **Controle do Instrutor**
- Botões de **Dificuldade** e **Forçar Desbloqueio** protegidos por chave
- Chave padrão: `instrutor2024`
- Sessão expira automaticamente após **5 minutos** de inatividade

### 📊 **Painel de Informações**
- Placar de vitórias, derrotas e empates
- Status do jogo em tempo real
- Histórico das últimas jogadas
- Indicador de quadrante atual

### 🎨 **Interface Visual**
- Design moderno com gradientes e efeitos de transparência
- Tema claro com fundo `#E9EDF2`
- Responsivo para desktop e mobile
- Feedback visual para cada ação

---

## 🕹️ Como Jogar

1. **Digite as coordenadas** no campo `(x, y)` (ex: `1, -1`)
2. **Clique em "🚀 Jogar"** ou pressione `Enter`
3. O computador **responde automaticamente** com uma jogada
4. **Vença 3 vezes** para desbloquear o clique no canvas
5. Após liberado, você pode **clicar diretamente** no tabuleiro

### 📌 Regras Importantes
- **Posição ocupada?** A vez passa automaticamente para o computador
- **Coordenadas válidas:** Apenas valores entre `-2` e `2` (grade 5x5)
- **Formato:** `x, y` (ex: `2, -1` ou `0, 1`)

---

## 🚀 Tecnologias Utilizadas

| Tecnologia | Descrição |
|------------|-----------|
| **HTML5** | Estrutura semântica da página |
| **CSS3** | Estilização, responsividade e animações |
| **JavaScript** | Lógica do jogo e interatividade |
| **Canvas API** | Renderização do tabuleiro cartesiano |

---

## 📁 Estrutura do Projeto
```
jogo-da-velha-cartesiano/<br>
├── index.html # Arquivo principal (tudo em um único arquivo)<br>
├── README.md # Este arquivo<br>
└── LICENSE # Licença MIT<br>
```
---

## 🛠️ Como Usar

### Opção 1: Abrir diretamente no navegador

1. Baixe o arquivo `index.html`
2. Abra-o em qualquer navegador moderno (Chrome, Firefox, Edge, etc.)
3. Comece a jogar!

### Opção 2: Hospedar no GitHub Pages

1. Faça um fork deste repositório
2. Ative o GitHub Pages nas configurações
3. Acesse: https://pedrohms11.github.io/JogoDaVelhaCartesiana/

### Opção 3: Servidor local

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/jogo-da-velha-cartesiano.git

# Navegue até o diretório
cd jogo-da-velha-cartesiano

# Abra o arquivo no navegador
```
## Habilidades Desenvolvidas
✅ Localização de pontos no plano cartesiano

✅ Identificação de quadrantes

✅ Leitura e escrita de coordenadas (x, y)

✅ Pensamento estratégico

✅ Resolução de problemas

✅ Lógica de programação

## 🔐 Chave do Instrutor
A chave padrão é instrutor2024 (pode ser alterada no código).

O que a chave libera:

🎯 Botão de Dificuldade (Fácil / Médio / Difícil)

🔓 Botão Forçar Desbloqueio (libera o clique sem precisar das 3 vitórias)

Tempo de sessão: 5 minutos (após isso, os botões são bloqueados novamente)

## 🌟 Destaques do Projeto
Design Responsivo: Funciona em desktop, tablet e smartphone

Acessibilidade: ARIA labels e navegação por teclado

Interatividade: Digitação de coordenadas, clique, feedback em tempo real

Conteúdo Didático: Ensina coordenadas, quadrantes e lógica de jogo

Código Limpo: Bem comentado e organizado

Proteção para Instrutor: Botões sensíveis protegidos por chave
## 📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
## 👨‍🏫 Autor
Pedro Moura

📧 Email: Pedro.moura@fiemg.com.br

🎓 Professor de Desenvolvimento de Sistemas

🤖 Especialista em Robótica Educacional

## 🙏 Agradecimentos
Font Awesome - Ícones (se utilizados)

GitHub Pages - Hospedagem gratuita

Todos os alunos que testaram e deram feedback!

## 🐛 Reportar Problemas
Encontrou um bug? Abra uma issue no GitHub.

## ⭐ Como Contribuir
Faça um fork do projeto

Crie sua branch (git checkout -b feature/AmazingFeature)

Commit suas mudanças (git commit -m 'Add some AmazingFeature')

Push para a branch (git push origin feature/AmazingFeature)

Abra um Pull Request

## 📞 Contato
Para dúvidas, sugestões ou colaborações:

📧 Email: Pedro.moura@fiemg.com.br





