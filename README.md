# va-Product-Card

Este es un paquete de pruebas NPM

### Victor Alvarez Rojas

## Ejemplo

```
import { ProductImage, ProductTitle, ProductButton } from 'aun-no-defino-nombre';
```

```
   <ProductCard
                product={product}
                initialValues={{
                    count: 4,
                    maxCount: 10
                }}
            >
                {
                    ({ reset }) => (
                        <>
                            <ProductImage />
                            <ProductTitle />
                            <ProductButton />
                        </>
                    )
                }
    </ProductCard>
```
