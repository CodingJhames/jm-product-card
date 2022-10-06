
# Jm-Product-Card

This a test package to deploy in NPM

## Jhames Mejía

### Example:

```
import { ProductCard,ProductImage,ProductTitle,ProductButtons } from 'jm-product-card'
```

```
<ProductCard 
    product={product }
    initialValues={{
        count: 4,
        // maxCount: 10,
    }}
>
    {
        ( { reset,count, increaseBy, isMaxCountReached, maxCount }  ) => (
        <>
            <ProductImage />
            <ProductTitle />
            <ProductButtons />

        </>
        )
    }

</ProductCard>
```