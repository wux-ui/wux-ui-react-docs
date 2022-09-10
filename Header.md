# Usage

```jsx
<WuX.Header
   title='WuX-UI-React Debug Page'
   small='Menu'
   option={[
       ['Github', 'https://github.com/wux-ui/wux-ui-react'],
       ['Offical Page', 'https://wux-ui.tk/', true]
   ]}
/>
```

# Parameter

name|describe|necessary (y / n)|type
:-:|:-:|:-:|:-:
title|a string as the title|y|*string*
small|a button for displaying options on the mobile terminal|n|*string*
option|an array and links each item of the array to the second item displayed on the right with the first item as the title|n|*HeaderOption[]*
type|a string to specify the type of Header element|n|*HeaderTypes*