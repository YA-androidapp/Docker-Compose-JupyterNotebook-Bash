# Docker-Compose-JupyterNotebook-Bash

Jupyter notebook with Bash kernel

---

```sh
$ docker-compose up -d && docker-compose logs # URL( http://127.0.0.1:8888/?token=************************************************ ) を確認する

# ログからではなく起動中のコンテナでURLを確認する場合
$ docker-compose exec bashnote jupyter notebook list
```

---

Copyright (c) 2021 YA-androidapp(https://github.com/YA-androidapp) All rights reserved.
