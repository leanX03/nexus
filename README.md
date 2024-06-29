<p align = "center">
    <a href = "https://t.me/thelittlestoryteller_bot"><img src = "https://i.postimg.cc/Xq68M3Sy/logo-tr-small.png" title = "it's a logo!">
</p>

<p align = "center">
    <a href = "LICENSE"><img src = "https://img.shields.io/badge/License-MIT-081f41?logo=homepage&logoColor=209ed5"></a>
    <a href = "https://www.python.org/downloads/"><img src = "https://img.shields.io/badge/Language-Python_v3.9-081f41?logo=python&logoColor=209ed5"></a>
    <img src = "https://img.shields.io/badge/Version-0.1.1-081f41?logo=v&logoColor=209ed5">
</p>

<p align = "center">
    <a href = "https://t.me/thelittlestoryteller_bot"><img src = "https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=209ed5&center=true&random=false&width=435&lines=Nexus;Simplicity+and+flexibility!"></a>
</p>

<h2>Installation</h2>

Install with `pip`

```bash
$ python -m install nexus_tool
```

<h2>Usage</h2>

Import `nexus_tool` in your project

```python
from nexus_tool import Logger

variabl = Logger()
```

After that you can use `INFO` | `WARN` and `ERROR`

```python
variabl.log("Some information", "INFO")
variabl.log("Some bad!", "WARN")
variabl.log("Some broken!!!", "ERROR")

#Output:
[29-06-2024 | 8:15:31] main.py | LOG.INFO -- Some information
[29-06-2024 | 8:15:31] main.py | LOG.WARN -- Some bad
[29-06-2024 | 8:15:31] main.py | LOG.ERROR -- Some broken!!!
```

Also, you can use `Logger.ask` to use stylized analogue of `input()`

```python
user_data = variabl.ask("Password: ")

#Output:
soon...
```