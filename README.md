
Тест Руфье

Описание: Данное приложение позволит с помощью теста Руфье
провести первичную диагностику здоровья сердечно-сосудистой 
системы.


![](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/th5xamgrr6se0x5ro4g6.png)


## Documentation

[Офф Сайт библиотеки kivy](https://kivy.org/#home)


## Run Locally

Здесь прдеставлены модули 

```bash
  from kivy.app import App
from kivy.uix.screenmanager import ScreenManager, Screen
from kivy.uix.boxlayout import BoxLayout
from kivy.uix.label import Label
from kivy.uix.button import Button
from kivy.uix.textinput import TextInput
from kivy.core.window import Window
from kivy.uix.scrollview import ScrollView
 
from instructions import txt_instruction, txt_test1, txt_test2, txt_test3, txt_sits
from ruffier import test

from seconds import Seconds
from sits import Sits
from runner import Runner

```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

