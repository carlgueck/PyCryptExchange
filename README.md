CryptsyPythonAPI
================

API for Cryptsy.com Exchange utilizing completely built-in functions and utilities of Python 3.\*.

Example Usage
-------------
Create buy order for dgc, market id 26, then cancels all orders you have for dgc
```python
import Cryptsy
Exchange = Cryptsy.Cryptsy('KEY HERE', 'SECRET HERE')
print(Exchange.createOrder(26, "Buy", 100, 0.00000001))       # Buy 100 dgc at .00000001 each
print(Exchange.cancelMarketOrders(26))                        # Cancels all orders in market 26, dgc
```



Authors Note And Contact
-------------
If you have any questions or concerns email me at carlgueck@gmail.com
This is mostly unchanged from https://github.com/ScriptProdigy/CryptsyPythonAPI

Donations 
-------------
Send all donations to this cryptsy trade key please! :)
3f40c9a5c80db7bc1dafa5687f00acc37230f78c

TODO
---
Add other markets' APIs.
