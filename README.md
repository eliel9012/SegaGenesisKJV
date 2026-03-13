# Mega Drive Bible (SGDK)

## English

Homebrew Sega Mega Drive / Genesis project that lets you browse and read Bible books and chapters directly on the console.

### Features

- book selection screen with scrolling list
- chapter selection grid
- in-game reading mode with wrapped text and vertical scrolling
- splash screen and custom UI palette

### Requirements

- [SGDK](https://github.com/Stephane-D/SGDK) installed locally
- Mega Drive toolchain available under `$HOME/SGDK`

### Build

```bash
make
```

This generates `bible.bin` from the project sources.

### Controls

- `UP/DOWN`: select book
- `A` or `START`: open chapters or confirm
- `B`: go back
- `C`: return to books from reading mode

### Project Structure

- `main.c`: UI, navigation, and rendering logic
- `bible_data.c` / `bible_data.h`: Bible data tables
- `res/`: visual assets and SGDK resource definitions
- `tools/`: helper scripts used during content preparation

### License

No license file is currently included.

## Português

Projeto homebrew para Sega Mega Drive / Genesis que permite navegar e ler livros e capítulos da Bíblia diretamente no console.

### Funcionalidades

- tela de seleção de livros com lista rolável
- grade de seleção de capítulos
- modo de leitura com quebra de texto e rolagem vertical
- splash screen e paleta visual personalizada

### Requisitos

- [SGDK](https://github.com/Stephane-D/SGDK) instalado localmente
- toolchain do Mega Drive disponível em `$HOME/SGDK`

### Build

```bash
make
```

Isso gera `bible.bin` a partir do código-fonte do projeto.

### Controles

- `UP/DOWN`: selecionar livro
- `A` ou `START`: abrir capítulos ou confirmar
- `B`: voltar
- `C`: voltar para a lista de livros a partir da leitura

### Estrutura do Projeto

- `main.c`: lógica de UI, navegação e renderização
- `bible_data.c` / `bible_data.h`: tabelas de dados bíblicos
- `res/`: assets visuais e definições de recursos do SGDK
- `tools/`: scripts auxiliares usados na preparação do conteúdo

### Licença

Ainda não há arquivo de licença incluído.
