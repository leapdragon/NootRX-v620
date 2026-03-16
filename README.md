


# NootRX-v620

This is a DOUBLY unsupported post of a hacked up version of NootRX by ChefKiss, created after I bought and installed
multiple Radeon v620 cards for local inference only to find out it knocked out my display.

The original kext (and this one) treat the first supported card they find as the card for MacOS desktop display.
The only difference is that this one puts a bunch of the common Navi cards in an allowlist and the Radeon Pro v620
*isn't in the allowlist.*

Net effect: If you happen to have a Navi/RDNA2 card (in my case, RX6700XT) for output, and Radeon Pro v620 cards for
other projects or things like local LLM inference, you won't have to play with "which card goes in which slot" to get
NootRX to give you disply+Metal on Mac OS. This is important becasue it can be a real battle to get the cards into
a case in the first place given their size; the last thing you want to do is be fighting which card goes in which slot.

Hope this helps someone.

Original NootRX project is Copyright © 2023-2024 ChefKiss. The NootRX project is licensed under the `Thou Shalt Not Profit License version 1.5`. See `LICENSE`.

> Original repository of NootRX [here](https://chefkiss.dev/applehax/nootrx) for more information.

Thanks [Acidanthera](https://github.com/Acidanthera) for the UnfairGVA patches in [WhateverGreen](https://github.com/Acidanthera/WhateverGreen).
