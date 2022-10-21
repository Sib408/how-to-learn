# Одностраничный сайт о методиках обучения
проектная работа Сайт о методиках обучения. Практика расширенных возможнотей HTML, CSS и использование БЭМ структуры Nested.
## Функциональность

+  HTML тег `iframe`

  ```HTML
  <iframe  class="video__iframe" width="515" height="316" src="https://www.youtube.com/embed/arj7oStGLkU" title="YouTube video player" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope;
  picture-in-picture" allowfullscreen></iframe>
  ```
+ CSS свойство трансформации `transition`
```CSS
.link-opacity {
  transition: opacity 0.3s ease-in-out ;
}
.link-opacity:hover {
  opacity: 0.65;
}
  ```

+  Директива `@keyframes`
и  CSS-анимация `animaition`
```CSS
@keyframes rotation {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

.rotation {
  animation: rotation 20s linear infinite;
}
  ```
+ БЭМ-структура Nested

## Планируемое обновление

+ верстка формы для комметариев- использование тега `form`
+ подлючение шрифтов локально `@font-face`
