# Hello, Mermaid!

![Static Badge](https://img.shields.io/badge/documentation-markdown-000?style=for-the-badge&logo=markdown&logoColor=white&labelColor=101010)
![Static Badge](https://img.shields.io/badge/diagrams-mermaid-FF3670?style=for-the-badge&logo=mermaid&logoColor=white&labelColor=101010)

> This repository is licensed under the terms of the [Apache License 2.0](LICENSE).


## Diagram Types

### 1. Flowchart

```mermaid
graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;
```

### 2. Sequence diagram

```mermaid
sequenceDiagram
  participant Alice
  participant Bob
  Alice->>John: Hello John, how are you?
  loop HealthCheck
    John->>John: Fight against hypochondria
  end
  Note right of John: Rational thoughts <br/>prevail!
  John-->>Alice: Great!
  John->>Bob: How about you?
  Bob-->John: Jolly good!
```


> Made with '\u{2665}' (♥) by Jesús Domínguez [@bluefeatherdev](https://github.com/bluefeatherdev)
