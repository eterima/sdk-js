# epilot SDK

Javascript SDK monorepo for epilot

## Quick Start

```sh
npm install --save epilot-sdk
```

```
import { getClient } from 'epilot-sdk/entity';

const entityClient = await getClient();
await entityClient.createEntity({ slug: 'contact' }, { name: 'My Contact' });
```

## Documentation

https://docs.epilot.io/docs/architecture/sdk
