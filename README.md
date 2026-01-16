<h2 id="sobre-o-projeto">1. 🔢 Analisador de Números Dinâmico 🔢</h2>

![Status do Deploy](https://img.shields.io/badge/Status-Online-brightgreen)
![Tecnologias](https://img.shields.io/badge/Tecnologias-HTML%20%7C%20CSS%20%7C%20JS-blueviolet)
[![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/analisador-numeros/blob/main/LICENSE)

![Analisador de Números](src/imagens/iMac-24-1120x630.png)

Bem-vindo ao **Analisador de Números**! Esta aplicação web interativa permite ao usuário cadastrar uma lista de valores numéricos entre 1 e 100. Ao finalizar a entrada de dados, o sistema realiza o processamento estatístico do array, fornecendo o total de itens, o maior e menor valor, a soma e a média aritmética dos dados informados.

---

## 📚 Tabela de Conteúdo

| 🔢 O Projeto | 🛠️ Técnico | 🤝 Comunidade |
| :---: | :---: | :---: |
| [![1. Sobre](https://img.shields.io/badge/1%20-%20Sobre-4CAF50)](#sobre-o-projeto) | [![5. Destaques](https://img.shields.io/badge/5%20-%20Destaques-607D8B)](#destaques-tecnicos) | [![9. Código](https://img.shields.io/badge/9%20-%20Código-795548)](#codigo-fonte) |
| [![2. Techs](https://img.shields.io/badge/2%20-%20Techs-2196F3)](#tecnologias-utilizadas) | [![6. Repositório](https://img.shields.io/badge/6%20-%20Repo-009688)](#codigo-fonte) | [![10. Créditos](https://img.shields.io/badge/10%20-%20Créditos-607D8B)](#créditos) |
| [![3. Acessar](https://img.shields.io/badge/3%20-%20Acessar-FF9800)](#como-acessar) | [![7. Contribuir](https://img.shields.io/badge/7%20-%20Contribuir-3F51B5)](#como-contribuir) | [![11. Licença](https://img.shields.io/badge/11%20-%20Licença-E91E63)](#licenca) |
| [![4. Funções](https://img.shields.io/badge/4%20-%20Funções-9C27B0)](#funcionalidades) | [![8. FAQ](https://img.shields.io/badge/8%20-%20FAQ-FFC107)](#faq) | [![12. Perfil](https://img.shields.io/badge/12%20-%20Perfil-212121)](#perfil-do-github) |

---

<h2 id="tecnologias-utilizadas">2. ⚙️ Tecnologias Utilizadas</h2>

| Camada | Tecnologias | Descrição |
| :--- | :--- | :--- |
| **Frontend** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) | Interface limpa com foco em usabilidade e feedback visual. |
| **Lógica** | ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) | Manipulação de arrays, validações lógicas e cálculos aritméticos. |
| **Apoio** | ![Gemini](https://img.shields.io/badge/Gemini-8E75C2?style=flat-square&logo=googlegemini&logoColor=white) | Auxílio na padronização documental e refinamento de funções. |

---

<h2 id="como-acessar">3. 🚀 Como Acessar</h2>

Clique no botão abaixo para testar o Analisador de Números agora mesmo:

<div align="left">
  <a href="https://domisnnet.github.io/analisador-numeros/" target="_blank">
    <img alt="Botão Acessar" src="src/imagens/botão.webp" height="70" width="70" />
  </a>
</div>

---

<h2 id="funcionalidades">4. 🧩 Funcionalidades Principais</h2>

O sistema foi projetado para evitar erros de entrada e fornecer dados precisos:

| Funcionalidade | Descrição |
| :--- | :--- |
| ✅ **Validação em Tempo Real** | Restrição de números apenas entre 1 e 100. |
| 🚫 **Prevenção de Duplicatas** | O algoritmo verifica se o número já foi inserido na lista antes de adicionar. |
| 📊 **Relatório Estatístico** | Exibe Maior, Menor, Soma e Média ao clicar em "Finalizar". |
| 🧹 **Reset Inteligente** | O campo de input é limpo e recebe foco automaticamente após cada inserção. |
| 📦 **Histórico Visual** | Uso de um elemento `select` para listar os valores cadastrados. |

---

<h2 id="destaques-tecnicos">5. 💻 Destaques Técnicos</h2>

Neste projeto, apliquei conceitos fundamentais de engenharia de software front-end:

### 🔄 Manipulação de Arrays
Utilização do objeto `Array` para armazenar os valores e métodos como `.includes()` para verificação de duplicidade, garantindo a integridade dos dados coletados.

### 📐 Cálculos de Agregação
Implementação de laços de repetição (`for in`) para percorrer a lista e extrair valores de pico (máximo e mínimo), além de acumuladores para somatório e cálculo de média com precisão decimal (`toFixed(2)`).

---

<h2 id="codigo-fonte">6. 📂 Repositório</h2>

Explore o código fonte ou clone o projeto para estudos:

[![Repositório](https://img.shields.io/badge/Repositório-Domisnnet%2Fanalisador--numeros-1DB954?style=for-the-badge&logo=github)](https://github.com/Domisnnet/analisador-numeros)

---

<h2 id="como-contribuir">7. 🤝 Como Contribuir</h2>

Siga os passos abaixo para fortalecer este projeto:

| Fase | Ação | Link / Comando |
| :---: | :--- | :--- |
| **01** | **Fork** | [![Fork](https://img.shields.io/badge/-Fazer%20Fork-blue?style=flat-square&logo=github)](https://github.com/Domisnnet/analisador-numeros/fork) |
| **02** | **Branch** | `git checkout -b feature/NovaEstatistica` |
| **03** | **Commit** | `git commit -m 'feat: cálculo de mediana adicionado'` |
| **04** | **Push** | `git push origin feature/NovaEstatistica` |
| **05** | **PR** | [![Abrir PR](https://img.shields.io/badge/-Abrir%20PR-green?style=flat-square&logo=git)](https://github.com/Domisnnet/analisador-numeros/compare) |

---

<h2 id="faq">8. 🧠 Perguntas Frequentes</h2>

<details>
<summary><strong>Por que o limite é entre 1 e 100 ❓</strong></summary>
<p>📏 <strong>Resposta:</strong> Este limite foi definido para fins didáticos e para manter a interface do seletor organizada, mas pode ser facilmente alterado na função <code>isNaN()</code>.</p>
</details>

<details>
<summary><strong>O que acontece se eu finalizar sem números ❓</strong></summary>
<p>⚠️ <strong>Resposta:</strong> O sistema possui um tratamento de erro que exibe um alerta (<code>window.alert</code>) solicitando a inserção de valores antes de gerar o relatório.</p>
</details>

<details>
<summary><strong>Os resultados são perdidos ao atualizar a página ❓</strong></summary>
<p>🔄 <strong>Resposta:</strong> Sim. Como os dados são armazenados em uma variável de estado simples (array na memória RAM), ao atualizar a página (F5), a lista é resetada.</p>
</details>

---

<h2 id="codigo-fonte">9. 💻 Código Fonte</h2>

Acesse diretamente os arquivos de script e estilo:

[![Código](https://img.shields.io/badge/Código%20Fonte-Acessar-795548?style=for-the-badge&logo=github)](https://github.com/Domisnnet/analisador-numeros/tree/main)

---

<h2 id="créditos">10. 📝 Créditos & Reconhecimentos</h2>

O **Analisador de Números** foi desenvolvido como parte de um roteiro de estudos práticos:

| Atribuição | Responsável / Recurso | Descrição |
| :--- | :--- | :--- |
| **Dev & Lógica** | **DomisDev** | Implementação das funções de validação, cálculo e manipulação de DOM. |
| **Educação** | **Curso em Vídeo** | Base teórica e exercícios propostos pelo Prof. Gustavo Guanabara. |
| **Design** | **DomisDev** | Estilização CSS e paleta de cores personalizada para o projeto. |
| **Apoio Técnico** | **Google Gemini** | Revisão de documentação e padronização para o padrão King-Domfy. |

### 🎯 Missão do Projeto
> "Consolidar o conhecimento sobre a tríade Web (HTML/CSS/JS), focando especialmente na lógica de programação e no tratamento de arrays em JavaScript Vanilla."

---

<h2 id="licenca">11. 📄 Licença</h2>

Este projeto está licenciado sob a [![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/analisador-numeros/blob/main/LICENSE)

---

<h2 id="perfil-do-github">12. 👨‍💻 Perfil do GitHub</h2>

<a href="https://github.com/Domisnnet"> <img src="src/imagens/DomisDev.png" width="120" alt="Acessar perfil GitHub"> </a>