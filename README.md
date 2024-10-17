# React_Native_Credit_Card_Input


```bash
yarn install

yarn example ios
# or
yarn example android
# or
yarn example web
```

# Components

## LiteCreditCardInput
| Prop               | Type                                      | Description                                                   |
|--------------------|-------------------------------------------|---------------------------------------------------------------|
| `autoFocus`        | `boolean`                                 | Optional. Specifies if the input should auto-focus.            |
| `style`            | `ViewStyle`                               | Optional. Custom style for the component's container.          |
| `inputStyle`       | `TextStyle`                               | Optional. Custom style for the input fields.                   |
| `placeholderColor` | `string`                                  | Optional. Color for the placeholder text.                      |
| `placeholders`     | `{ number: string; expiry: string; cvc: string; }` | Optional. Custom placeholders for the input fields.            |
| `onChange`         | `(formData: CreditCardFormData) => void`  | Required. Callback function called when form data changes.     |
| `onFocusField`     | `(field: CreditCardFormField) => void`    | Optional. Callback function called when a field gains focus.   |

## CreditCardInput
| Prop               | Type                                      | Description                                                   |
|--------------------|-------------------------------------------|---------------------------------------------------------------|
| `autoFocus`        | `boolean`                                 | Optional. Specifies if the input should auto-focus.            |
| `style`            | `ViewStyle`                               | Optional. Custom style for the component's container.          |
| `labelStyle`       | `TextStyle`                               | Optional. Custom style for the labels.                         |
| `inputStyle`       | `TextStyle`                               | Optional. Custom style for the input fields.                   |
| `placeholderColor` | `string`                                  | Optional. Color for the placeholder text.                      |
| `labels`           | `{ number: string; expiry: string; cvc: string; }` | Optional. Custom labels for the input fields.                  |
| `placeholders`     | `{ number: string; expiry: string; cvc: string; }` | Optional. Custom placeholders for the input fields.            |
| `onChange`         | `(formData: CreditCardFormData) => void`  | Required. Callback function called when form data changes.     |
| `onFocusField`     | `(field: CreditCardFormField) => void`    | Optional. Callback function called when a field gains focus.   |


## CardView

| Prop              | Type                                                      | Description                                                    |
|-------------------|-----------------------------------------------------------|----------------------------------------------------------------|
| `focusedField`    | `'name' \| 'number' \| 'expiry' \| 'cvc'`                 | Optional. Specifies which field is currently focused.           |
| `type`            | `CreditCardIssuer`                                        | Optional. Specifies the type of the credit card issuer.         |
| `name`            | `string`                                                  | Optional. The name on the credit card.                          |
| `number`          | `string`                                                  | Optional. The credit card number.                               |
| `expiry`          | `string`                                                  | Optional. The expiry date of the credit card.                   |
| `cvc`             | `string`                                                  | Optional. The CVC code of the credit card.                      |
| `placeholders`    | `{ number: string; expiry: string; cvc: string; name: string; }` | Optional. Custom placeholders for the input fields.            |
| `style`           | `ViewStyle`                                               | Optional. Custom style for the component's container.           |
| `fontFamily`      | `string`                                                  | Optional. Custom font family for the text.                      |
| `imageFront`      | `ImageSourcePropType`                                     | Optional. Image source for the front of the credit card.        |
| `imageBack`       | `ImageSourcePropType`                                     | Optional. Image source for the back of the credit card.         |
