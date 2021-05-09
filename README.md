# ouput-replace-webpack-plugin
replace output file content

### Install
Install with npm:

`$ npm install --save-dev ouput-replace-webpack-plugin`

### Examples

```
new OutputReplaceWebpackPlugin({
    file: 'test.json',
    match: /\d+\/\d+\/\d+/g,
    conent: formatDate(new Date(), 'yyyy-MM-dd~hh:mm:ss'),
})
```
