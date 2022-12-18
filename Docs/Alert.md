# Usage

```jsx
<WuX.Alert type='primary'>Primary</WuX.Alert>
```

In DOM: 
```wux-jsx-render
<WuX.Alert type='primary'>Primary</WuX.Alert>
<WuX.Alert type='secondary'>Secondary</WuX.Alert>
<WuX.Alert type='success'>Success</WuX.Alert>
<WuX.Alert type='info'>Info</WuX.Alert>
<WuX.Alert type='warning'>Warning</WuX.Alert>
<WuX.Alert type='error'>Error</WuX.Alert>
<WuX.Alert type='light'>Light</WuX.Alert>
<WuX.Alert type='primary'>
    <WuX.Alert type='icon'>:D</WuX.Alert>
    Icon
</WuX.Alert>
<WuX.Alert type='primary'>
    AlertWithOption
    <WuX.Alert type='option-group'>
        <span>x</span>
    </WuX.Alert>
</WuX.Alert>
:wux-jsx-render
```

# Parameter

name|describe|necessary (y / n)|type
:-:|:-:|:-:|:-:
type|a string to specify the type of the Alert element|y|*`AlertTypes`*

## type

type|example|describe
:-:|:-:|:-:
[*`AlertTypes`*](../Types/Alert.md#alerttypes)|`'primary'`|a string of the type of Alert element