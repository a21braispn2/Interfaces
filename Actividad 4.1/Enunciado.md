# 🧩 Actividade 4.1 — Proxecto Práctico: Curso de Principios de Maquetación CSS

## 🎯 Obxectivo

Crear unha páxina web promocional para unha tenda de produtos electrónicos utilizando técnicas de maquetación con CSS. A páxina debe estar ben estruturada empregando propiedades de posicionamento, flotantes e contedores.

---

## 🏗️ 1. Estrutura Principal

- Barra de navegación fixa na parte superior con 4 seccións:

  - Inicio
  - Produtos
  - Sobre nós
  - Shop
  - Contactar

- Cabeceira con imaxe principal e un **call to action** para realizar unha compra:

  - O botón terá `href="#"` como enlace ficticio.

- Sección principal:

  - Título centrado.
  - Tres tarxetas destacando produtos como:
    - Portátiles
    - Refrixeración líquida
    - Gafas de realidade virtual

- Sección con imaxes e descricións (Lorem Ipsum) sobre características dos produtos.

- Galería de imaxes con miniaturas organizadas en varias filas.

- Pé de páxina con:
  - Información de contacto
  - Iconas de redes sociais
  - Sección de copyright

---

## 🎨 2. Maquetación e Estilo

- Usar `float` para organizar elementos como imaxes e texto.
- O botón de chamada á acción debe estar centrado e usar `position` para situarse correctamente na cabeceira.
- O menú principal debe permanecer fixo ao desprazarse (`position: fixed`).
- Usar `clear` para evitar que os elementos flotantes afecten á maquetación.
- Aplicar `box-sizing: border-box` para controlar o tamaño das caixas.
- Os contedores principais (`nav`, `.container`, `footer`) deben ter:
  - `max-width: 1200px`
  - `min-width: 576px`
- A imaxe da cabeceira debe ter unha **lixeira transparencia** (`opacity` ou `rgba`).
- Usar **pseudo-elementos** para:
  - Engadir liñas decorativas na sección principal (`::before`, `::after`)
  - Estilizar a primeira letra da sección de contido (`::first-letter`)

---

## 📌 3. Resumo

- Menú de navegación fixo na parte superior.
- Cabeceira con imaxe de fondo e opacidade para destacar o texto.
- Tarxetas organizadas en filas con imaxes e texto centrado (`float` + `width`).
- Sección de imaxes flotantes con descricións dos produtos.
- Galería de imaxes con miniaturas organizadas en filas:
  - Teléfonos
  - Portátiles
  - Accesorios
  - Outros aparellos electrónicos
- Pé de páxina con:
  - Enderezo de contacto
  - Copyright
  - Iconas de redes sociais

---

## 📁 Entrega

Debes entregar:

- Ficheiro `HTML` coa estrutura da páxina.
- Directorio `CSS` co estilo e maquetación.
- Directorio `img` coas imaxes necesarias.
