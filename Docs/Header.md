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
<details>
<summary>Mobile Phones</summary>

```wux-html-phone
<WuX.Header
    title='WuX-UI-React Debug Page'
    small='Menu'
    option={[
        { title: 'Github', link: 'https://github.com/wux-ui/wux-ui-react-docs' },
        { title: 'Offical Page', link: 'https://react.wux-ui.tk/', bold: true },
        <JsxElement />
    ]}
/>
:wux-html-phone
```

</details>

<details>
<summary>Computer</summary>

```wux-html-full
<WuX.Header
    title='WuX-UI-React Debug Page'
    small='Menu'
    option={[
        { title: 'Github', link: 'https://github.com/wux-ui/wux-ui-react-docs' },
        { title: 'Offical Page', link: 'https://react.wux-ui.tk/', bold: true },
        <JsxElement />
    ]}
/>
:wux-html-full
```

</details>

<details>
<summary>Fixed Header</summary>

```wux-html-full
<WuX.Header
    title='Fixed Header'
    small='Menu'
    option={[
        { title: 'Github', link: 'https://github.com/wux-ui/wux-ui-react-docs' },
        { title: 'Offical Page', link: 'https://react.wux-ui.tk/', bold: true },
    ]}
    type='fixed'
/>
:wux-html-full
```

</details>

# Parameter

name|describe|necessary (y / n)|type
:-:|:-:|:-:|:-:
type|a string to specify the type of Header element|n|*`HeaderTypes`*
title|a string as the title|y|*`string`*
small|a button for displaying options on the mobile terminal|n|*`string`*
option|an array with objects which is consist of `title`, `link` and `bold`|y|*`(HeaderOption \| JSX.Element)[]`*
children|/|n|*`JSX.Element`*

## type

type|example|describe
:-:|:-:|:-:
[*`HeaderTypes`*](../Types/Header.md#headertypes)|`'fixed'`|a string of the type of Header element
[*`HeaderOption`*](../Types/Header.md#headeroption)|`{ title: 'Offical Page', link: 'https://react.wux-ui.tk/', bold: true },`|an object