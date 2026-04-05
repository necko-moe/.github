<div align="center">
  <img src="static/necko3_banner.png" alt="necko3 banner" width="768"/>
  <h1>necko3</h1>
</div>

* * *

## WHO IS NECKO3? 😳🫣

**necko3** is a heavy-duty, industrial-grade processing beast wrapped inside a lightweight, cute shell (if that makes it easier to digest).

It was created as an alternative to bloated enterprise solutions, focusing on a simple principle: you pay strictly for what you use and not a penny more, while getting an experience that is equal to, if not better than, the giants.

<br />
Thanks to its incredible backend efficiency, you can host her on a potato-grade $0.01 VPS (actually, please don't do that), and she won't even realize the host is overselling by 10000%.
<br />
The architecture allows you to use it for personal needs or as a foundation for your own custodial payment gateway :)

### Key Features
* **Non-custodial** (Servers DO NOT store mnemonics).
* Uses **xpub** to derive billions of accounts that only you can access.
* Incredibly lightweight and fast.
* Fault-tolerant and adaptable (all blockchain parameters are configurable).
* Ability to connect **ANY** EVM network, as long as there is an RPC node.
* Fully asynchronous architecture.
* 0 missed blocks and proper handling of chain reorgs.
* REST API, Webhooks, and Swagger included with the backend.
* The crate (logic) is decoupled from the backend (wrapper) and frontend.

## Modules

| Name                                                                       | Description                                                                                                                                                 |
|----------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <a href="https://github.com/necko-moe/necko3-frontend">necko3-frontend</a> | Represents an admin panel (consumes only backend endpoints requiring an API key from .env).                                            |
| <a href="https://github.com/necko-moe/necko3-payment-page">necko3-paymemt-page</a>                                                        | Represents a payment page for end-users (consumes only public backend endpoints).                                                      |
| <a href="https://github.com/necko-moe/necko3-backend">necko3-backend</a>   | The Backend. A web wrapper over `necko3-core`. Serves as both a usage example for the crate and a fully functioning module.                                 |
| <a href="https://github.com/necko-moe/necko3-core">necko3-core</a>         | The juicy, meaty core containing all the logic. DB calls, payment processing, blockchain listening, transaction validation — it all rests on her shoulders. |

## License

The project and all repositories are distributed under the **MIT License**. Feel free to use, modify, and distribute <3

* * *

## Support

Want to make necko1 employed or donate enough for a Triple Whopper? Contact me -> <a href=https://t.me/everyonehio>Telegram</a> or <a href="mailto:meow@necko.moe">Mail me</a> (I rarely check that). I don't accept direct card transfers, just so you know
