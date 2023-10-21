<!-- Start SDK Example Usage -->


```typescript
import { PetStore } from "PetStore";

(async () => {
    const sdk = new PetStore();

    const res = await sdk.pets.createPets();

    if (res.statusCode == 200) {
        // handle response
    }
})();

```
<!-- End SDK Example Usage -->