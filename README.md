# bare-type

Cross-realm type predicates for Bare.

```
npm i bare-type
```

## Usage

```js
const type = require('bare-type')

if (type(123).isNumber()) {
  console.log(123, 'is a number')
}
```

## License

Apache-2.0

<!-- bare-refgen:api start -->

## API

### Type

#### `new Type(type: number)`

**Parameters**

| Parameter | Type     | Default | Description |
| --------- | -------- | ------- | ----------- |
| `type`    | `number` | —       | —           |

#### `isArguments(): boolean`

#### `isArray(): boolean`

#### `isArrayBuffer(): boolean`

#### `isAsyncFunction(): boolean`

#### `isBigInt(): boolean`

#### `isBigInt64Array(): boolean`

#### `isBigUint64Array(): boolean`

#### `isBoolean(): boolean`

#### `isDataView(): boolean`

#### `isDate(): boolean`

#### `isError(): boolean`

#### `isExternal(): boolean`

#### `isFloat16Array(): boolean`

#### `isFloat32Array(): boolean`

#### `isFloat64Array(): boolean`

#### `isFunction(): boolean`

#### `isGenerator(): boolean`

#### `isGeneratorFunction(): boolean`

#### `isInt16Array(): boolean`

#### `isInt32(): boolean`

#### `isInt32Array(): boolean`

#### `isInt8Array(): boolean`

#### `isMap(): boolean`

#### `isModuleNamespace(): boolean`

#### `isNull(): boolean`

#### `isNumber(): boolean`

#### `isObject(): boolean`

#### `isPromise(): boolean`

#### `isProxy(): boolean`

#### `isRegExp(): boolean`

#### `isSet(): boolean`

#### `isSharedArrayBuffer(): boolean`

#### `isString(): boolean`

#### `isSymbol(): boolean`

#### `isTypedArray(): boolean`

#### `isUint16Array(): boolean`

#### `isUint32(): boolean`

#### `isUint32Array(): boolean`

#### `isUint8Array(): boolean`

#### `isUint8ClampedArray(): boolean`

#### `isUndefined(): boolean`

#### `isWeakMap(): boolean`

#### `isWeakRef(): boolean`

#### `isWeakSet(): boolean`

### Functions

#### `type(value: unknown): Type`

Return a `Type` wrapping `value`, exposing `is*()` predicates to test its runtime type across realms.

**Parameters**

| Parameter | Type      | Default | Description                 |
| --------- | --------- | ------- | --------------------------- |
| `value`   | `unknown` | —       | The value to wrap and test. |

<!-- bare-refgen:api end -->
