# Tailwind CSS 

# Installation process:

- For installing TypeScript in existing React: https://create-react-app.dev/docs/adding-typescript/

- For installing tailwindcss follow: https://tailwindcss.com/docs/installation/using-vite

## Tailwind CSS: It's a css framework that's built on top of css.

## Why Use Tailwind CSS instead of Plain CSS:

We use Tailwind CSS instead of plain CSS because it makes building websites much faster and more consistent.
Advantage of Tailwind CSS: 
-   We can put all the styles directly into the class attribute using Tailwind's words: 
    ```<button class="**bg-red-500 p-4 rounded-lg**">.```
    
-   Instead of writing this in a seperate file of Plain CSS:
    ```<button class="my-big-red-button">```
    ```background-color: red; padding: 16px; border-radius: 8px;.```



### Margins:

- **m-4**: margin on all sides

- **mt-8**: margin-top 

- **mb-2**: margin-bottom

- **mx-auto**: margin-left:auto; margin-right:auto

- **my-5**: margin-top, margin-bottom

- **ml-6**: margin-left

- **mr-5**: margin-right

- **-m-4**: Pushes element into neighbors by 1rem

- **-mt-8**: Pulls element up by 2rem

### Paddings:

- **p-4**: padding on all sides

- **pt-8**: padding on top

- **px-8**: padding-left, padding-right

- **py-1**: padding-top, padding-bottom

- **pr-6**: padding-right

- **pl-5**: padding-left

### Sizing:

- **w- or -h** : Fixed width & height (Syntax: w-40, h-24)

- **w-px or h-px** : Fixed width and height of exactly 1px. (Syntax: w-px, h-px) 

- **size-** : Sets both width & height to same value. (Syntax: size-16)

- **w-[value] or h-[value]** : Allows to specify any custom value not on scale using bracket
(Syntax:  w-[150px];  h-[3rem]; )

- **w-full or h-full** : Sets width or height to 100% of parent element. (Syntax: w-full, h-full)

- **w- or h-** : Sets using common fractions. (Syntax: w-1/2, h-3/4)

- **size-full** : Sets both width and height to 100%. (Syntax: size-full)

- **min-w / max-w** : Sets min & max width of an element. (Syntax: min-w-0; max-w-xl;)

- **min-h / max-h** : Sets min & max height. (Syntax: min-h-full, max-h-screen)

- **w-screen** : Sets width to 100vw(100% of viewport width) (Syntax: w-screen)

- **h-screen** : Sets height to 100vh (100% of viewport height) (Syntax: h-screen)

- **Dynamic Viewport** : (dvh, lvh, svh) (Syntax: h-dvh => height: 100dvh)

- **w-auto / h-auto** : Resets size to default 'auto' for browser. (Syntax: w-auto, h-auto)

- **w-fit / h-fit** : Sets size based on content size but constrained by container. (Syntax: w-fit, h-fit)

- **w-min / h-min** : Smallest size element can be used without overflowing its content. (Syntax: w-min, h-min)

- **w-max / h-max** : Largest size can be used without wrapping its content. (Syntax: w-max, h-max)

### Typography:

- **font-sans** 

- **font-serif**

- **font-mono**

- **text-xs to text-2xl** : Set of utilities for common sizes, increasing in size as number gets larger

- **text-sm** : Sets text to small size.

- **text-lg** : Sets text to large size.

- **text-xs** : Extra small

- **text-base** : The default size for body paragraphs.

- **text-xl** : Extra large

- **text-2xl to text-9xl**

- **font-light** :	Thin weight (e.g: 300).

- **font-normal** : Default weight (e.g: 400).

- **font-bold** :	Thick weight (e.g: 700).

- **italic**

- **not-italic**

- **text-gray-500**

- **text-blue-600**

- **text-red-700**

- **text-left**

- **text-center**

- **text-right**

- **text-justify** : Stretches text to both left and right edges.

### Color & Background:

- **bg-red-500**

- **bg-sky-100**

- **bg-gray-800**

- **bg-white**

- **text-green-600**

- **text-gray-900**

- **text-white**

### Borders & Shadows

- **border**	: Applies a default 1-pixel border to all sides.

- **border-2** : Applies a thicker border (2px)

- **border-t-4** : Applies a border only to the top side, with a width of 4px.

- **border-x-8**	: Applies a border to both the left and right sides.

- **border-blue-500**

- **border-gray-300**

- **rounded-sm** : A small, subtle rounding of all corners

- **rounded-lg** : A larger, more noticeable rounding.

- **rounded-full** : Makes the element perfectly circular (great for profile pictures).

### Flex:

- **flex**	Sets the element's display type to flex.

- **flex-row** : Arranges items horizontally (left to right) along the main axis. This is the default if no direction is specified.

- **flex-col** : Arranges items vertically (top to bottom) along the main axis.

- **justify-start** : Lines items up at the beginning of the main axis (left in a row, top in a column).

- **justify-center** : Centers the items as a group along the main axis.

- **justify-end** :	Lines items up at the end of the main axis (right in a row, bottom in a column).

- **justify-between** : Puts equal space between the items, pushing the first and last to the edges.

- **items-start** : Aligns items to the beginning of the cross axis.

- **items-center** : Centers the items along the cross axis.

- **items-end**	: Aligns items to the end of the cross axis.

- **items-stretch**	: Stretches the items to fill the entire cross axis space. This is often the default.

### Display:

- **block** : The element takes up the full available width and forces a line break after it. Examples: div tag, h1 tag and p tag.

- **inline** : The element only takes up as much width as necessary for its content. It does not force a line break, so other elements can sit next to it. Examples: span tag and a tag.

- **inline-block** : A combination: it renders next to other elements (like inline), but you can set its width and height (like block). Ideal for styling complex horizontal lists or buttons.

- **hidden** : Removes the element completely from the document flow. It takes up no space and is not visible.

#### Overflow:

- **overflow-hidden** : Cuts off any content that extends past the element's border. The content disappears; you cannot scroll to it.

- **overflow-scroll** : Always shows scrollbars (both horizontal and vertical), allowing the user to view the full content.

- **overflow-auto** : Only shows scrollbars when necessary. This is usually the best default for containers that might overflow.

- **overflow-x-scroll** : Controls only the horizontal overflow. Useful for tables that are too wide.

### Response prefixes:

- **sm** :	Small (e.g., Tablet portrait)

- **md** :	Medium (e.g., Tablet landscape)

- **lg** : Large (e.g: laptop)

- **xl** : Extra Large

- We can combine two classes: **lg:w-1/2, md:text-left**

- Always define the mobile look first, and then use prefixes to tell Tailwind what should change as the screen gets bigger.

### State:

- **E.g of hover** : bg-blue-700

- **E.g of focus** : border-indigo-500

### Grid System:

- Displays data in a grid (in a table with rows and columns)
  
- **grid** : Mandatory to define the element as a grid container.

- **grid-cols-4** : Defines the number of columns. We can use numbers up to 12.

- **grid-rows-3** : Defines the number of rows (less common than columns).

- **gap-6** : Sets spaces between the grids, we can use gap-x-*, gap-y-* for showing changes in particular section.

- **gap-x-n** : Sets only the horizontal column spacing.

- **gap-y-n** :	Sets only the vertical row spacing.

- **grid-flow-row**	: Sets item placement to proceed across rows first, then down (default).

- **grid-flow-col** : Sets item placement to proceed down columns first, then across.

- **grid-flow-dense** :	Allows items to fill in holes left by earlier items for better space usage.

- **col-span-1** : Makes the item span 1 column.

- **row-span-2** : Makes the item span 2 rows.

- **col-start-2** : Makes the item to begin with 2nd vertical grid line.

- **col-end-n/auto** : Specifies the vertical grid line number where the item should end.

- **row-start-n** : Specifies the horizontal grid line number where the item should start.

- **row-end-n** : Specifies the horizontal grid line number where the item should end.

- **col-span-full** : Forces the item to span the entire width of the grid, regardless of the column count.

- **row-span-full**	: Forces the item to span the entire height of the grid.

- **grid-cols-1** : Always applied.

- **md:grid-cols-3** : Applied from medium screens up.

- **lg:col-span-1** : Applied from large screens up.

- **justify-items-n** : Aligns grid items horizontally within their own cells (e.g., start, center, end).

- **justify-self-n** : Aligns a single grid item horizontally within its own cell.

- **content-n** : Aligns the grid tracks/content when there is extra space in the container (e.g., center, between).

- **items-n** : Aligns grid items vertically within their own cells (e.g., start, center, end).

- **self-n** : Aligns a single grid item vertically within its own cell.

- **place-items-n** : Shorthand for both justify-items and align-items.

- **place-content-n** : Shorthand for both justify-content and align-content.

- sm -> small screen, lg -> large screen, md -> medium screen, xl/2xl -> Extra large screen.
