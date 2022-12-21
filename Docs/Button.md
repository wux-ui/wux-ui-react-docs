# Usage

```jsx
<WuX.Button WuXType='primary'>Primary</WuX.Button>
```

In DOM: 
```wux-jsx-render
<div>
    <WuX.Button WuXType='primary'>Primary</WuX.Button>
    <WuX.Button WuXType='secondary'>Secondary</WuX.Button>
    <WuX.Button WuXType='success'>Success</WuX.Button>
    <WuX.Button WuXType='info'>Info</WuX.Button>
    <WuX.Button WuXType='warning'>Warning</WuX.Button>
    <WuX.Button WuXType='error'>Error</WuX.Button>
    <WuX.Button WuXType='light'>Light</WuX.Button>
</div>
<div>
    <WuX.Button WuXType={['primary', 'outline']}>Primary</WuX.Button>
    <WuX.Button WuXType={['secondary', 'outline']}>Secondary</WuX.Button>
    <WuX.Button WuXType={['success', 'outline']}>Success</WuX.Button>
    <WuX.Button WuXType={['info', 'outline']}>Info</WuX.Button>
    <WuX.Button WuXType={['warning', 'outline']}>Warning</WuX.Button>
    <WuX.Button WuXType={['error', 'outline']}>Error</WuX.Button>
    <WuX.Button WuXType={['light', 'outline']}>Light</WuX.Button>
</div>
<div>
    <WuX.Button WuXType={['primary', 'text']}>Primary</WuX.Button>
    <WuX.Button WuXType={['secondary', 'text']}>Secondary</WuX.Button>
    <WuX.Button WuXType={['success', 'text']}>Success</WuX.Button>
    <WuX.Button WuXType={['info', 'text']}>Info</WuX.Button>
    <WuX.Button WuXType={['warning', 'text']}>Warning</WuX.Button>
    <WuX.Button WuXType={['error', 'text']}>Error</WuX.Button>
    <WuX.Button WuXType={['light', 'text']}>Light</WuX.Button>
</div>
<div>
    <WuX.Button WuXType={['primary', 'xs']}>SuperSmall</WuX.Button>
    <WuX.Button WuXType={['secondary', 'sm']}>Small</WuX.Button>
    <WuX.Button WuXType={['success', 'md']}>Medium</WuX.Button>
    <WuX.Button WuXType={['info', 'lg']}>Large</WuX.Button>
    <WuX.Button WuXType={['warning', 'xl']}>SuperLarge</WuX.Button>
    <WuX.Button disabled>Disabled</WuX.Button>
    <WuX.Button WuXType='square'>Square</WuX.Button>
    <WuX.Button WuXType='default'>Default</WuX.Button>
    <WuX.Button WuXType='round'>Round</WuX.Button>
</div>
<div>
    <WuX.Button WuXType={['round', 'block']}>Block</WuX.Button>
</div>
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