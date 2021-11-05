<!-- This file is generated from the source code. Edit the files in /packages/hydrogen/src/components/CartProvider and run 'yarn generate-docs' at the root of this repo. -->

## Example code

```tsx
import {CartProvider} from '@shopify/hydrogen';

export function App() {
  return <CartProvider>{/* Your JSX */}</CartProvider>;
}
```

## Component type

The `CartProvider` component is a client component, which means that it renders on the client. For more information about component types, refer to [React Server Components](/custom-storefronts/hydrogen/framework/react-server-components).

## Related components

- [`AddToCartButton`](/api/hydrogen/components/cart/addtocartbutton)
- [`SelectedVariantAddToCartButton`](/api/hydrogen/components/product-variant/selectedvariantaddtocartbutton)
- [`CartCheckoutButton`](/api/hydrogen/components/cart/cartcheckoutbutton)

## Related hooks

- [`useCart`](/api/hydrogen/hooks/cart/usecart)
- [`useCartBuyerIdentityUpdateCallback`](/api/hydrogen/hooks/cart/usecartbuyeridentityupdatecallback)
- [`useCartDiscountCodesUpdateCallback`](/api/hydrogen/hooks/cart/usecartdiscountcodesupdatecallback)
- [`useCartLinesAddCallback`](/api/hydrogen/hooks/cart/usecartlinesaddcallback)
- [`useCartLinesRemoveCallback`](/api/hydrogen/hooks/cart/usecartlinesremovecallback)
- [`useCartLinesUpdateCallback`](/api/hydrogen/hooks/cart/usecartlinesupdatecallback)
- [`useCartCheckoutUrl`](/api/hydrogen/hooks/cart/usecartcheckouturl)
- [`useCartCreateCallback`](/api/hydrogen/hooks/cart/usecartcreatecallback)
- [`useCartLinesTotalQuantity`](/api/hydrogen/hooks/cart/usecartlinestotalquantity)