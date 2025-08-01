# ✨ VS Code Minimalista

Uma configuração visual limpa, moderna e eficiente para desenvolvedores que valorizam foco, estética e performance do Vscode.

## ⭐ Apoie este Projeto

Se você curtiu essa configuração minimalista do VS Code, considere deixar uma estrela no repositório! Isso ajuda:

- A dar visibilidade para o projeto 💡
- A manter ele ativo e atualizado 🔄
- E mostra que você valoriza conteúdo simples e bem feito ❤️

![Screenshot 1](https://i.imgur.com/L9TvP62.png)

| 📌 Basta clicar no botão ⭐️ "Star" no topo da página aqui no GitHub.

## 🖼️ Aparência do VS Code Minimalista

| ![Screenshot 1](https://i.imgur.com/t5H3urC.png) | ![Screenshot 2](https://i.imgur.com/SRMxjcu.png) |
| ------------------------------------------------ | ------------------------------------------------ |
| ![Screenshot 3](https://i.imgur.com/2YPyNBc.png) | ![Screenshot 4](https://i.imgur.com/4G1qTCz.png) |

## 🎯 Objetivo

Essa configuração transforma o Visual Studio Code em um ambiente de desenvolvimento minimalista e funcional, com foco em:

- ✨ Clareza visual
- ⚡ Produtividade
- 🧘‍♂️ Menos distrações

## ⚙️ Funcionalidades Habilitadas

- ✅ Formatação automática com Prettier ao salvar
- ✅ Salvamento automático com atraso
- ✅ Word wrap ativado
- ✅ Zoom com roda do mouse
- ✅ Importações automáticas ao mover arquivos JS/TS
- ✅ Linhas guias em `80` e `120` caracteres

## 🎨 Estilo Visual

| Elemento                | Configuração                     |
| ----------------------- | -------------------------------- |
| **Tema**                | `Oscura Midnight`                |
| **Ícones**              | `symbols`                        |
| **Fonte**               | `JetBrains Mono` (com ligaduras) |
| **Tamanho da fonte**    | `18px`                           |
| **Barra lateral**       | À direita                        |
| **Barra de atividades** | Na parte inferior                |
| **Status bar**          | Oculta                           |
| **Minimapa**            | Oculto automaticamente           |
| **Scrollbars**          | Completamente escondidas         |

## 📦 Requisitos

- Extensão recomendada:
  - [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  - [Symbols](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols)
  - [Oscura Theme (Oscura Midnight)](https://marketplace.visualstudio.com/items?itemName=Fey.oscura)
- Fonte recomendada:
  - [JetBrains Mono](https://www.jetbrains.com/pt-br/lp/mono/)

## 🔧 Acesso o Arquivo de Configuração `settings.json`

**Comando no vscode:** `ctrl + shift +  p`

```json
{
  "workbench.iconTheme": "symbols",
  "workbench.startupEditor": "none",
  "editor.fontSize": 18,
  "editor.fontFamily": "JetBrains Mono",
  "editor.lineHeight": 1.8,
  "editor.fontWeight": "bold",
  "files.autoSave": "afterDelay",
  "editor.tabSize": 2,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnType": true,
  "editor.formatOnSave": true,
  "workbench.activityBar.location": "bottom",
  "explorer.compactFolders": false,
  "editor.minimap.autohide": true,
  "editor.stickyScroll.enabled": false,
  "workbench.sideBar.location": "right",
  "editor.mouseWheelZoom": true,
  "workbench.statusBar.visible": false,
  "editor.wordWrap": "on",
  "editor.scrollbar.vertical": "hidden",
  "editor.scrollbar.horizontal": "hidden",
  "editor.scrollbar.verticalScrollbarSize": 0,
  "editor.scrollbar.horizontalScrollbarSize": 0,
  "window.menuBarVisibility": "toggle",
  "breadcrumbs.enabled": false,
  "editor.rulers": [80, 120],
  "workbench.editorAssociations": {
    "*.avi": "default"
  },
  "workbench.colorTheme": "Oscura Midnight",
  "chat.commandCenter.enabled": false,
  "window.commandCenter": false,
  "editor.fontLigatures": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "window.titleBarStyle": "custom",
  "files.associations": {
    ".env*": "dotenv"
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "keyword.other.dotenv",
        "settings": {
          "foreground": "#FF000000",
          "fontStyle": "italic"
        }
      }
    ]
  },
  "git.autofetch": true,
  "workbench.tree.enableStickyScroll": false,
  "workbench.secondarySideBar.defaultVisibility": "hidden",
  "workbench.secondarySideBar.showLabels": false
}
```

## ✍️ Quer usar?

1. Vá para Cmd/Ctrl + Shift + P → Preferences: Open Settings (JSON)
2. Copie e cole o conteúdo acima
3. Instale as extensões e temas recomendados
4. Reinicie o VS Code

## 👨🏿‍💻 Autor

Feito com foco em minimalismo, performance e design por:

**Vittor F. Serra**  
[GitHub](https://github.com/DevVittor) | [Twitter](https://x.com/vittorFserra)

> Sinta-se à vontade para abrir uma _issue_ ou me chamar para sugestões ou melhorias
