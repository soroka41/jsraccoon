# Конвертирование нативных CSS переменных с помощью функции calc
Используйте CSS функцию calc для конвертирования переменных в нужные вам значения:
```css
div {
	--foo: 50;
	width: var(--foo)px; /* не сработает */
	height: calc(var(--foo) * 1px); /* сработает */
	background: #f06;
}
```
