# Проверка оформления {#sec-article-example}

См. @sec-article-purpose. В @tbl-article-files перечислены материалы примера.

| Материал | Назначение |
|:---------|:-----------|
| Markdown | Текст статьи |
| BibLaTeX | Общая база литературы |

: Материалы учебной статьи {#tbl-article-files}

Схема @fig-article-flow создаётся локально.

```{mermaid}
%%| label: fig-article-flow
%%| fig-cap: "Сборка отдельной статьи"
flowchart LR
    A[Текст статьи] --> B[HTML PDF Word]
```

Для проверки математической разметки приведена формула:

$$
a^2 + b^2 = c^2
$$ {#eq-article-example}

Ссылка на неё: @eq-article-example.
