# [WIP] Smart-Contract Operator Pythonic Framework (Scoph)

**Scoph** —Smart-Contract Operator Pythonic Framework— is a Pythonic framework and a library
that facilitates the development of blockchain smart-contract Kubernetes operators.

## Examples

```py
import scopf

CONTRACT = '0xad9EB619Ce1033Cc710D9f9806A2330F85875f22'

@scopf.on.event(CONTRACT, 'Transfer')
def on_transfer(data, **kwargs):
    print(f"And here we are! Creating: {data}")
```
