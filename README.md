# Affectum

## Affectum Documentation

- ✅ **Liberdade**
- ✅ **Comunidade interativa**
- ✅ **Sem necessidade de se indentificar**
- ✅ **Plataforma amiga do usuário**
- ✅ **Perfis personalizados**

### Project Structure

The Astro docs template supports multiple langauges out of the box. The default theme only shows `en` documentation, but you can enable multi-language support features by adding a second language to your project.

To add a new language to your project, you'll want to extend the current `src/pages/[lang]/...` layout:

```diff
 📂 src/pages
 ┣ 📂 pt
 ┃ ┣ 📜 casodeuso.md
 ┃ ┣ 📜 introducao.md
 ┃ ┣ 📜 requisitos.astro
+ ┣ 📂 pt
+ ┃ ┣ 📜 casodeuso.md
+ ┃ ┣ 📜 introducao.md
+ ┃ ┣ 📜 requisitos.astro
```