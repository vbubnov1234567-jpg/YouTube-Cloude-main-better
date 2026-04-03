# YouTube-Cloude
---
## Вам понадобится установить зависимости
><br/>import cv2
<br/>import numpy as np
<br/>import os
<br/>import math
<br/>import subprocess
<br/>import tempfile
<br/>import shutil
<br/>import sys
<br/>import re
<br/>import hashlib
---
# Для кодирования любого файла:
><br/><code>python c.py endcode FILENAME.xxx FILENAME.mp4</code>
><br/>или <code>python c.py e FILENAME.xxx FILENAME.mp4</code>
<br/>Где .xxx - это расширение вашего файла, который находится в одной папке с coder.py. Пишете в этой папке, нажав на название и написав cmd, и вводите это
---
# Для декодирования видеофайла:
><br/><code>python c.py decode FILENAME.mp4</code>
><br/>или <code>python c.py d FILENAME.mp4</code>
---
## Ключ шифрования
><br/>Вы можете создать в папке с coder.py файл <code>key.txt</code> и написать внутри него ключ шифрования любой длины. После этого код будет учитывать присутствие key.txt при кодирование файлов и в дальнейшем такие видеофайлы обратно декодироваться правильно будуту только с правильным ключом, указанном в key.txt.
---
# Вот в чем улучшение:
><br/>1. Название короче (c.py вместо coder.py)
><br/>2. Ютф-8 вместо латин-1 (можете название файла на русском писать)
><br/>3. Можно одной буквой декодить и кодить (смотрите выше)
><br/>Можете создать две папки, где одни файлы без key.txt, а другой с ним
