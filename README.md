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
![image](https://github.com/69Jesse/Python-Json-Class-Creator/assets/104533077/c51ce602-c04c-49ef-92de-699144d9bbe0)
into
![image](https://github.com/69Jesse/Python-Json-Class-Creator/assets/104533077/cfcfd359-b6fb-4dfa-b636-9a846478dcc5)
with ease
(check `example.json`, `example.py`, `usage.py`)
