# Flex-embed

@suitcss' [components-flex-embed](https://github.com/suitcss/components-flex-embed/)

## Installation

- npm : `npm install --save totem-flex-embed`
- bower : `bower install --save totem-flex-embed`

## Available classes

- `o-flex-embed`
- `o-flex-embed__ratio`
- `o-flex-embed__ratio--3by1`
- `o-flex-embed__ratio--2by1`
- `o-flex-embed__ratio--16by6`
- `o-flex-embed__ratio--4by3`

## Usage 

Basic exemple

```
<div class="o-flex-embed">
	<div class="o-flex-embed__ratio o-flex-embed__ratio--16by9"></div>
	<div class="o-flex-embed__content">
		<!-- img/iframe/embed/object content -->
	</div>
</div>
```

Custom aspect ratio using CSS

```
.o-flex-embed__ratio--4by1 {
    padding-bottom: 25%;
}
```

Custom aspect ratio using inline style

```
<div class="o-flex-embed">
	<div class="o-flex-embed__ratio" style="padding-bottom: 25%"></div>
	<div class="o-flex-embed__content">
		<!-- img/iframe/embed/object content -->
	</div>
</div>
```
