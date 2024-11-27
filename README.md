# Template Sass

Este repositório fornece um modelo inicial para projetos que utilizam **Sass**, estruturado com a metodologia **ITCSS** (Inverted Triangle CSS). Esse modelo promove uma organização clara, escalabilidade e facilidade na manutenção de estilos, sendo ideal para projetos de qualquer porte.

## 🚀 Funcionalidades

- Organização baseada na metodologia **ITCSS**, que divide os estilos em camadas hierárquicas.
- Estrutura inicial completa para trabalhar com **Sass (SCSS)**.
- Facilita o crescimento do projeto sem comprometer a manutenção ou criar conflitos de estilos.
- Ideal para projetos que exigem organização modular e reutilização de código.

## 🗂️ Estrutura de Pastas

A estrutura do projeto segue as diretrizes do ITCSS, organizando os estilos em camadas lógicas e hierárquicas:

```
src/
├── settings/    # Configurações globais: variáveis, cores, tipografia, breakpoints, etc.
├── tools/       # Mixins e funções utilitárias.
├── base/        # Resets e normalizadores básicos.
├── typography/  # Estilos relacionados a fontes e textos básicos.
├── layout/      # Estilos para layout e estrutura de página (grids, containers, etc.).
├── components/  # Componentes específicos: botões, formulários, modais, etc.
├── theme/       # Temas ou variações de estilos globais.
├── utilities/   # Classes utilitárias de uso específico (helper classes).
```

Cada pasta possui um papel específico no ciclo de desenvolvimento, ajudando a manter o código CSS limpo e modular.

## 📦 Instalação

1. **Clone este repositório:**

   ```bash
   git clone https://github.com/eriveltondasilva/template.sass.git
   ```

2. **Acesse o diretório do projeto:**

   ```bash
   cd template.sass
   ```

3. **(Opcional) Instale dependências necessárias (como ferramentas de compilação Sass):**

   ```bash
   npm install
   ```

4. **Compile os arquivos Sass:**
   ```bash
   npx sass src:dist
   ```
   Certifique-se de ajustar os caminhos conforme a estrutura do seu projeto.

## 📖 Sobre ITCSS

**ITCSS** (Inverted Triangle CSS) é uma metodologia para organizar e estruturar estilos CSS de forma hierárquica. Ela é dividida em camadas que seguem uma ordem lógica, permitindo que:

- Estilos genéricos e configurações venham primeiro.
- Estilos específicos de componentes e utilitários sejam aplicados por último.
- O código CSS permaneça modular, fácil de ler e escalável.

Essa abordagem reduz conflitos de estilo e facilita a manutenção de projetos complexos.

## 🤝 Como Contribuir

Contribuições são sempre bem-vindas! Veja como você pode colaborar:

1. Faça um **fork** do projeto.
2. Crie uma **branch** para sua funcionalidade:
   ```bash
   git checkout -b minha-nova-funcionalidade
   ```
3. Envie suas alterações:
   ```bash
   git push origin minha-nova-funcionalidade
   ```
4. Abra um **Pull Request** explicando suas alterações.

## 📜 Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE). Você pode usá-lo livremente, mas lembre-se de atribuir crédito ao autor.

**Desenvolvido com 💙 por [Erivelton Silva](https://github.com/eriveltondasilva/)**
