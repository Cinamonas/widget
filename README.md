# TokenJS Widget

## Demo

[tokenjs.com/#demo](https://tokenjs.com/#demo)

## Installation

1. `npm install tokenjs` or `yarn add tokenjs`
2. Initialize widget:
    ```js
    import TokenJS from 'tokenjs'
    
    const tokenJs = new TokenJS({
      apiKey: '<YOUR-API-KEY>',
      campaignId: '<YOUR-CAMPAIGN-id>',
    })
    ``` 
3. Open the widget on some user action:
    ```js
    tokenJs.open()
    ```

## API

### Constructor options

```js
new TokenJS({
  
  // (required) API key
  apiKey: '',
  
  // (required) Campaign ID
  campaignId: '',
  
  // (optional) Checkout URL
  checkoutUrl: '',
})
```

### Instance methods

- `open()` – opens the widget
- `close()` – closes the widget
- `destroy()` – destroys instance of the widget

## Development

1. `yarn`
2. `yarn serve`

## License

[MIT](./LICENSE)
