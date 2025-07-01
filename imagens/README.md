# Projeto Integrador I - Template Quarto

Este repositório é um modelo de documentação para o Projeto Integrador I dos cursos de Ciência de Dados e Machine Learning do CEUB. Ele está formatado segundo as normas da ABNT e estruturado com o sistema Quarto.

## 📄 Estrutura

- `index.qmd`: introdução geral
- `01-introducao.qmd`: contexto e objetivos
- `02-metodologia.qmd`: tecnologias, ferramentas e processos
- `03-desenvolvimento.qmd`: arquitetura, código e decisões
- `04-resultados.qmd`: imagens, gráficos, resultados
- `05-conclusao.qmd`: aprendizados e próximos passos
- `referencias.qmd`: lista de referências (com suporte `.bib`)
- `refs.bib`: arquivo BibTeX para citações
- `contracapa.tex`: contracapa em LaTeX para ABNT
- `imagens/`: coloque aqui capturas de tela e diagramas
- `_quarto.yml`: configurações do projeto

## 🚀 Como Usar

### Localmente (RStudio ou terminal)

1. Instale o Quarto: https://quarto.org/docs/get-started/
2. Certifique-se de que você possui LaTeX instalado (ex: [TinyTeX](https://yihui.org/tinytex/))
3. No terminal, rode:

```bash
quarto render
```

### Alternativa com GitHub Actions (renderização automática - opcional)

Será adicionado um arquivo `.github/workflows/render.yml` para gerar o PDF automaticamente a cada commit.

## 📌 Regras

- Documentação é obrigatória e será avaliada com base na completude e clareza.
- O código deve estar hospedado em repositório GitHub e ser referenciado neste relatório.

## 👨‍🏫 Suporte

Em caso de dúvidas, consulte os materiais no Moodle ou entre em contato com o professor responsável.
