# Usage

```jsx
<WuX.Header
   title='WuX-UI-React Debug Page'
   small='Menu'
   option={[
        { title: 'Github', link: 'https://github.com/wux-ui/wux-ui-react-docs' },
        { title: 'Offical Page', link: 'https://react.wux-ui.tk/', bold: true },
        <JsxElement />
    ]}
/>
```

In DOM: 
<nav class="wux-header wux-header-fixed"><span class="wux-header-title">WuX-UI-React</span><button class="wux-header-small-option-group">Menu</button><span class="wux-header-option-group"><a class="wux-header-option" href="https://react-docs.wux-ui.tk/">Docs</a><a class="wux-header-option" href="https://github.com/wux-ui/wux-ui-react">Github</a></span></nav>

# Parameter

name|describe|necessary (y / n)|type
:-:|:-:|:-:|:-:
type|a string to specify the type of Header element|n|*`HeaderTypes`*
title|a string as the title|y|*`string`*
small|a button for displaying options on the mobile terminal|n|*`string`*
option|an array with objects which is consist of `title`, `link` and `bold`|y|*`(HeaderOption | JSX.Element)[]`*
children|/|n|*`JSX.Element`*