# Usage

```jsx
<WuX.Alert type='primary'>Primary</WuX.Alert>
```

## Type

Use `type` to specify the type of the Alert element

### Normal

Includes `primary`, `secondary`... and so on  

JSX of example:  
```jsx
<>
    <WuX.Alert type='primary'>Primary</WuX.Alert>
    <WuX.Alert type='secondary'>Secondary</WuX.Alert>
    <WuX.Alert type='success'>Success</WuX.Alert>
    <WuX.Alert type='info'>Info</WuX.Alert>
    <WuX.Alert type='warning'>Warning</WuX.Alert>
    <WuX.Alert type='error'>Error</WuX.Alert>
    <WuX.Alert type='light'>Light</WuX.Alert>
</>
```
  
<details>
<summary>In DOM</summary>

```wux-jsx-render
<WuX.Alert type='primary'>Primary</WuX.Alert>
<WuX.Alert type='secondary'>Secondary</WuX.Alert>
<WuX.Alert type='success'>Success</WuX.Alert>
<WuX.Alert type='info'>Info</WuX.Alert>
<WuX.Alert type='warning'>Warning</WuX.Alert>
<WuX.Alert type='error'>Error</WuX.Alert>
<WuX.Alert type='light'>Light</WuX.Alert>
:wux-jsx-render
```

</details>

### Icon

Use `icon` type Alert element in a Normal type Alert element  

JSX of example:  
```jsx
<WuX.Alert type='primary'>
    <WuX.Alert type='icon'>:D</WuX.Alert>
    Icon
</WuX.Alert>
```

<details>
<summary>In DOM</summary>

```wux-jsx-render
<WuX.Alert type='primary'>
    <WuX.Alert type='icon'>:D</WuX.Alert>
    Icon
</WuX.Alert>
:wux-jsx-render
```

</details>

### Option Group

Use `option-group` type Alert element in a Normal type Alert element  

JSX of example:  
```jsx
<WuX.Alert type='primary'>
    AlertWithOption
    <WuX.Alert type='option-group'>
        <span>x</span>
    </WuX.Alert>
</WuX.Alert>
```

<details>
<summary>In DOM</summary>

```wux-jsx-render
<WuX.Alert type='primary'>
    AlertWithOption
    <WuX.Alert type='option-group'>
        <span>x</span>
    </WuX.Alert>
</WuX.Alert>
:wux-jsx-render
```

</details>

# Parameter

name|describe|necessary (y / n)|type
:-:|:-:|:-:|:-:
type|a string to specify the type of the Alert element|y|*`AlertTypes`*

## type

type|example|describe
:-:|:-:|:-:
[*`AlertTypes`*](../Types/Alert.md#alerttypes)|`'primary'`|a string of the type of Alert element