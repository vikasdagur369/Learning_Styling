# Tailwind CSS Notes

## Text Color Syntax

```html
"text-blue-500"
```

## Background Color Syntax

```html
"bg-blue-600"
```

## Text Decoration

- `line-through` - put a line through text
- `underline` - underline the text
- `underline decoration-blue-400` - will underline the text with blue color
- `overline decoration-blue-400` - will underline the text with blue color

## Margins

- `m-5` - provides margin for all directions.
- `mx-5`, `my-5`, `mt-5`, `mr-5`, `ml-5`, `mb-5`

## Arbitrary Spacing

- `m-[200px]`, `mx-[200px]`, etc.

## Padding

- `p-5` - provides padding for all directions.
- `px-5`, `py-5`, `pt-5`, `pr-5`, `pl-5`, `pb-5`

## Space Between X

```html
<div class="flex space-x-4">
    <div>01</div>
    <div>02</div>
    <div>03</div>
    <div>04</div>
</div>
```

Similarly, we can use `space-y-4` but we have to write `flex flex-col`.

## Font Size

We can adjust the size of text easily using:

- `text-xs`
- `text-sm`
- `text-base`
- `text-lg`
- `text-xl`
- `text-3xl`
- `text-nxl`

## Font Family

- `font-sans`
- `font-serif`
- `font-mono`

## Font Weight

Defines the boldness of the fonts:

- `font-light`
- `font-normal`
- `font-medium`
- `font-semibold`
- `font-bold`

## Letter Spacing

Increases the space between letters in a word:

```html
<p class="tracking-tight"></p>
<p class="normal"></p>
<p class="wide"></p>
<p class="widest"></p>
```

## Text Alignment

```html
<p class="text-left"></p>
<p class="text-center"></p>
<p class="text-right"></p>
```

## Decoration Style

```html
<p class="underline decoration-solid"></p>
<p class="underline decoration-double"></p>
<p class="underline decoration-dotted"></p>
<p class="underline decoration-dashed"></p>
<p class="underline decoration-wavy"></p>
<p class="underline offset-2"></p> <!-- Adds 2 space between text and underline -->
```

## Text Transformation

```html
<p class="normal-case"></p>
<p class="uppercase"></p>
<p class="lowercase"></p>
<p class="capitalize"></p>
```

## Width All Around

Defines the width of a div:

```html
<div class="w-5"></div>
<div class="w-1/2"></div> <!-- Takes half width of its parent div -->
```

## Height All Around

```html
<div class="h-5"></div>
<div class="h-1/2"></div>
<div class="h-full"></div> <!-- Works similar to width -->
```

## Min Height

Sets the minimum height of an element:

```html
<div class="min-h-full"></div> <!-- Takes minimum height of parent div -->
<div class="max-h-5"></div> <!-- Will not take height more than 5 -->
```

## Full Screen Height

```html
<div class="h-screen"></div> <!-- Takes height of full screen -->
```

## Width Auto

```html
<div class="w-auto"></div> <!-- Takes automatic width -->
```

## Positions

### Relative & Absolute

```html
<div class="relative">
    <div class="absolute"></div>
</div>
```

If the parent div is relative and the child div is absolute, then it will not go out of the parent div.

## Display

```html
<span class="inline">Hello</span> <!-- Width & height property will not work, it will keep the span in line only -->
<span class="inline-block"></span> <!-- We can give height and width to span -->
<span class="block"></span> <!-- It will remain in line -->
```

# Tailwind CSS Notes:-

## Text color syntax:

"text-blue-500"

## Background color syntax:

"bg-blue-600"

## text decoration :

"line-through" - put a line through text

"underline" - underline the text

"underline decoration-blue-400" - will underline the text with blue color

## "overline decoration-blue-400" - will underline the text with blue color.

## Margins :

"m-5" - provides margin for the all directions.
"mx-5", "my-5", "mt-5", "mr-5", "ml-5", "mb-5"

## Arbitrary spacing :

"m-[200px]",mx-[200px]" etc

## padding :

"p-5" - provides padding for the all directions.
"px-5", "py-5", "pt-5", "pr-5", "pl-5", "pb-5"

## Space b/w X:

<div class="flex space-x-4"> -> flex will arrange all div in vertical manner, parellel to each other and space-x-4 will  add distance of 4 between them.
   
    <div>01</div>
    <div>02</div>
    <div>03</div>
    <div>04</div>

</div>

-> similiarly we can use space-y-4 but we have to write "flex flex-col"

## Font size :

we can adjust size of text easily using :

"text-xs","text-sm","text-base","text-lg","text-xl","text-3xl",,,,"text-nxl"

## font-family :

"font-sans", "font-serif", "font-mono"

## font - weight:

-> it will define the boldness of the fonts.

"font-light"
"font-normal"
"font-medium"
"font-semibold"
"font-bold"

## letter-spacing :

-> it will increase the space between letters in a word.

<p class="tracking-tight">
<p class="normal">
<p class="wide">
<p class="widest">

## text-alignment :

<p class="text-left">
<p class="text-center">
<p class="text-right">

## decoration style:

<p class="underline decoration-solid">
<p class="underline decoration-double">
<p class="underline decoration-dotted">
<p class="underline decoration-dashed">
<p class="underline decoration-wavy">

<p class="underline offset-2"> -> it will add 2 space b/w text and underline.

## text transformation:

<p class="normal-case">
<p class="uppercase">

<p class="lowercase">
<p class="capitalize">

## width all around :

it will define the width of div

<div class="w-5">

<div class="w-1/2>

it will take half width of its parent div

## width all around :

<div class="h-5">
<div class="h-1/2"> 
<div class="h-full">

works similiar to width.

## Min height :

setting the minimum height of an element.

<div class="min-h-full""> -> will take minimum h of parent div.

<div class="max-h-5"> -> will not take height more than 5

## full screen height

<div class="h-screen"> -> will take height of full screen.

## width auto :

<div class="w-auto"> -> will take automatic heigtht

## Positions :

### relative & absolute :

<div class="relative">

    <div class="absolute"></div>

</div>

if parent div is relative and child div is absolute then it will not go out of parent div.

## Display :

<span class="inline"> Hello </span> -> now width & height property will not work, it wll keep the span in line only.

<span class="inline-block"></span> -> we can give h and w to span.

<span class="block> </span> -> it will remain in line

