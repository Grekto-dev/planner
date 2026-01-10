# 📅 Planner Semanal Interativo

![Version](https://img.shields.io/badge/version-1.2.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

> Uma ferramenta leve e eficiente para planejamento semanal, desenvolvida inteiramente em um único arquivo HTML (Single-File Application). Organize suas tarefas, gerencie seu tempo e exporte seu planejamento com facilidade.

---

## ✨ Funcionalidades

O Planner foi projetado para ser intuitivo e repleto de recursos úteis para produtividade:

- **🖱️ Drag & Drop Intuitivo:** Arraste tarefas livremente entre os dias da semana ou para a caixa de entrada (Inbox).
- **🎨 Cores Dinâmicas:** As tarefas mudam de cor automaticamente dependendo do dia da semana em que são alocadas.
- **➕ Gestão de Semanas:** Adicione ou remova semanas conforme necessário. O sistema calcula automaticamente as datas sequenciais.
- **⏱️ Cálculo de Tempo:** Visualização automática do total de horas/minutos planejados por dia.
- **💾 Salvar e Carregar:** Persistência de dados através de arquivos JSON (inclui suas configurações personalizadas).
- **🖼️ Exportar como Imagem:** Gere uma "foto" (JPEG) do seu planner com um clique para compartilhar ou imprimir.
- **↩️ Desfazer/Refazer:** Histórico de ações integrado para evitar erros acidentais.
- **🖨️ Modo de Impressão:** Layout CSS otimizado para impressão física em papel.

### ⚙️ Configurações Personalizáveis
Você pode ajustar o planner ao seu estilo:
* **Formato de data:** `DD/MM` ou `MM/DD`.
* **Unidade de tempo:** `Minutos` ou `Horas + Minutos`.

---

## 🚀 Como Usar

Não é necessária nenhuma instalação de dependências (npm, node, etc) ou servidor local!

1.  **Baixe** o arquivo `planner.html` (ou clone este repositório).
2.  **Abra** o arquivo diretamente em seu navegador web preferido (Chrome, Edge, Firefox, Safari).
3.  **Comece a planejar!**

> **Nota:** Para a funcionalidade de exportação de imagem funcionar corretamente, é necessária uma conexão com a internet na primeira execução para carregar a biblioteca `html2canvas` via CDN.

---

## ⌨️ Atalhos e Dicas

Para agilizar o seu uso, utilize os seguintes comandos:

| Ação | Comando / Interação |
| :--- | :--- |
| **Selecionar Tarefa** | Clique `1x` na tarefa |
| **Editar Data** | Clique `1x` na data do dia |
| **Editar Tarefa** | Clique `2x` no título ou tempo da tarefa |
| **Salvar Edição** | Pressione `Enter` |
| **Quebra de Linha** | Pressione `Shift + Enter` (ao editar texto) |
| **Mover Tarefa** | Arraste e solte com o mouse |

---

## 🛠️ Tecnologias Utilizadas

Este projeto foca na portabilidade e simplicidade:

* **HTML5, CSS3 e JavaScript (Vanilla):** Tudo consolidado em um único arquivo.
* **LocalStorage / File API:** Utilizados para leitura e escrita de arquivos JSON de backup.
* **[html2canvas](https://html2canvas.hertzen.com/):** Biblioteca utilizada para renderizar o DOM como imagem (carregada via CDN).

---

## 📦 Estrutura do Projeto

O repositório consiste essencialmente em um único arquivo principal:

```text
/
└── planner.html  # Contém toda a lógica (JS), estilos (CSS) e estrutura (HTML)
```

## 📝 Créditos
Desenvolvido por **Pedro Nogueira**.

Este projeto é open-source e pode ser modificado livremente. Se ele te ajudou, considere dar uma ⭐ no repositório!
