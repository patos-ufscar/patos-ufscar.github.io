# Blog
PATOS Blog - made with Hugo!

## Desenvolvimento do site

### Clonar repo
```bash
git clone [repo url]
```

### Iniciar submodules
```bash
git submodule init
git submodule update
```

### Rodar Hugo
```bash
hugo server -D
```

## Adicionar novo post

### Criar novo post com categoria
```bash
hugo new --kind [talk, flash_talk, post] [categoria]/[nome-da-pagina].md
```

### Criar novo post padrão
```bash
hugo new posts/[nome-do-post].md
```

## Trocar tema do Hugo
Atenção: Pode ser necessário configurar o tema do Hugo para o site funcionar corretamente.

### Adicionar novo tema
```bash
git submodule add [repo url] themes/[nome-do-tema]
```

### Remover tema antigo
```bash
git submodule deinit themes/[nome-do-tema]
git rm themes/[nome-do-tema]
```

## Links  úteis

- Doc Hugo: [https://gohugo.io/](https://gohugo.io/)
- Temas: [https://themes.gohugo.io/](https://themes.gohugo.io/)
