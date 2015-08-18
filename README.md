# bootstrap-MultiGrid
MultiGrid Mod for Bootstrap 3

Расширяет стандартную сетку bootstrap стилями для FullHD, 4k, 8k мониторов, а также для экранов менее 420px по ширине (hd, 4k, 8k, xxs  соответственно)

Подключить после css файла бутстрапа

Например:
```html
	<link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="css/bootstrap-multigrid.css" rel="stylesheet">
```
	

Стили для HD мониторов

col-hd-* (col-hd-6 займёт пол блока) на FullHD экране


Также работают col-xxs-12, col-4k-12 и col-8k-12 для малоэкранных (<420px), 4k и 8k  девайсов соответственно

.visible-hd, .visible-hd-block, .visible-hd-inline, .visible-hd-inline-block (будут показаны только на fullHD экранах)

.hidden-lg (будет скрыт на HD экране и останется без изменений на всех остальных)

.container тоже подновлён

