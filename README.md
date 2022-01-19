# django_git_merey



## Title
This is my To Do list app with Django+Postgresql
```html
Done by: Orynbassar Merey
Group:SE-2010
```

### Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [License](#lisense)

---

## Installation

* ### Django
```python $ pip install django```

* ### psycopg2
```python $ pip install psycopg2```

* ### PostgreSQL Database [Download](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)



[Back To The Top](#django_git_merey)

## Usage
After installing needed modules, just execute app.py, it will start server.

Then just go by port generated by server: http://127.0.0.1:8000/



```python
from django.shortcuts import render,redirect
from django.views.generic.list import ListView
from django.views.generic.edit import CreateView, UpdateView, DeleteView, FormView
from django.urls import reverse_lazy
from .models import ToDo
from django.contrib.auth.views import LoginView, LogoutView
from django.contrib.auth.mixins import LoginRequiredMixin
from django.contrib.auth.forms import UserCreationForm
from django.contrib.auth import login ``` 


## Examples
```html
1.User must register;
<img width="1440" alt="Снимок экрана 2022-01-18 в 18 02 52" src="https://user-images.githubusercontent.com/80208323/150103673-c75d9145-384e-42a4-bbba-6222a5950f7c.png">


2.User must create new task:
<img width="1440" alt="Снимок экрана 2022-01-18 в 18 02 11" src="https://user-images.githubusercontent.com/80208323/150103763-d6501aa8-14f1-47e4-baf4-004ab5d0e249.png">
<img width="1440" alt="Снимок экрана 2022-01-18 в 18 02 33" src="https://user-images.githubusercontent.com/80208323/150103786-60ab2624-304c-4f58-8cc2-513feb005d8d.png">

```
<img width="1440" alt="Снимок экрана 2022-01-18 в 18 02 52" src="https://user-images.githubusercontent.com/80208323/150104586-aaa74221-de39-4fd5-ae2f-405c47d2f9a1.png">

[Back To The Top](#django_git_merey)

## License

MIT License

Copyright (c) 2021 Overexm

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Back To The Top](#django_git_merey)



