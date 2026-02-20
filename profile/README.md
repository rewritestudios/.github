<div align="center">

# Rewrite

**SMS the way it should be** — simple, predictable and absurdly cheap.
Send transactional SMS and OTPs with **flat rate of ~$0.04 USD per SMS**, no contracts, no surprises and no paperwork.

Made for devs who want **reliability, excellent DX and total control** over SMS sending.

## Integrate in a few lines

</div>

```ts
import { Rewrite } from '@rewritejs/sdk';

const client = new Rewrite(process.env.REWRITE_API_KEY);

const { data, error } = await client.messages.send({
    to: '+5511999999999',
    message: 'You verification code is 482931',
});
```

<div align="center">

Just like that, the **Rewrite** way of being.

## Join the SMS revolution

**Rewrite** was born open source because we believe that critical infrastructure **should not be a black box.**

Contribute, discuss ideas, and help build the future of simple, affordable SMS messaging.

**Rewrite** — SMS the way it should be.

</div>
