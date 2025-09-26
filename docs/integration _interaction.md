# 9	Интеграционное взаимодействие
## 9.1.	Диаграмма последовательности

[![Оформление заказа через приложение](diagrams/sequence_diagram.jpg){: .hover-zoom }](diagrams/sequence_diagram.jpg){: target="_blank" }


```mermaid
    graph TD;
        A-->B;
        A-->C;
        B-->D;
        C-->D;
```

<style>
.hover-zoom {
    max-width: 100%;
    max-height: 600px;
    cursor: zoom-in;
    border: 2px solid #ccc;
    padding: 20px;
    object-fit: contain;
    display: block;
    margin: 25px auto;
    transition: transform 0.5s ease;
}

.hover-zoom:hover {
    transform: scale(1.8);
    z-index: 100;
    position: relative;
}
</style>
