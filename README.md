# Python-Json-Class-Creator

I spent a lot of time creating Python classes for Json data I got interaction with all kinds of APIs so I wrote a script to turn Json data into properly typehinted Python classes.

```py
JSON_DATA: list[dict[str, typing.Any]] = ...
# A list of data of the SAME FORMAT you get in any way, like API calls.

from create import create
create(name='SomeClass', data=JSON_DATA)
```
That's it! The classes get saved to `classes.py`.
The more data you supply, the more accurate it will be.

Example:

Turn
![image](https://github.com/69Jesse/Python-Json-Class-Creator/assets/104533077/157963c9-b50a-4818-a8a2-d7005e4cd6b6)
into
![image](https://github.com/69Jesse/Python-Json-Class-Creator/assets/104533077/14b6df36-a44d-45d8-aed4-0978531d0ce1)
with ease
