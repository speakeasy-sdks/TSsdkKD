<!-- Start SDK Example Usage [usage] -->
```typescript
import { PetStore } from "PetStore";

async function run() {
    const sdk = new PetStore();

    const res = await sdk.pets.createPets({
        id: 596804,
        name: "<value>",
    });

    if (res.statusCode == 200) {
        // handle response
    }
}

run();

```
<!-- End SDK Example Usage [usage] -->