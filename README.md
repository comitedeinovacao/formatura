# Formatura Senac Araçatuba - Gestão e Negócios

Sistema de apresentação para cerimônia de colação de grau do Senac Araçatuba, área de Gestão e Negócios.

## Funcionalidades

- **Apresentação animada**: Slides interativos com navegação por teclado e mouse.
- **Painel Admin**: Cadastro de turmas, alunos e músicas de entrada.
- **Upload de músicas**: Integração com Cloudinary para armazenamento de áudios.
- **Responsivo**: Funciona em desktops e dispositivos móveis.

## Como usar

1. Abra `admin.html` para cadastrar turmas e alunos.
2. Adicione músicas MP3 para cada aluno (opcional).
3. Salve os dados e abra `index.html` para a apresentação.
4. Navegue pelos slides com setas do teclado ou cliques.

## Hospedagem no GitHub Pages

1. Crie um repositório no GitHub.
2. Faça upload dos arquivos `index.html` e `admin.html`.
3. Vá em Settings > Pages > Source: Deploy from a branch > Branch: main > Save.
4. O site ficará disponível em `https://seu-usuario.github.io/nome-do-repo/`.

## Identidade Visual

- Cores: Azul Senac (#004587), Laranja (#F7941D)
- Fonte: Montserrat
- Animações suaves com CSS

## Desenvolvimento

- HTML5, CSS3, JavaScript puro
- Sem dependências externas (exceto Cloudinary para upload)

## Configuração Cloudinary

Para upload de músicas, configure as credenciais no `admin.html`:
- `CLOUD_NAME`: Seu cloud name do Cloudinary
- `UPLOAD_PRESET`: Preset de upload configurado

---

Senac Araçatuba · 2026