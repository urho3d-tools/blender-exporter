Urho3D-Blender
==============

Видеоинструкция: <https://www.youtube.com/watch?v=O0h12-2Hnq0>.

Для создания своего материала нужно клонировать один из библиотечных материалов (ноды этих материалов полностью повторяют шейдеры Urho3D).

Минимальная версия Блендера: 2.82 (так как использует ноду [compare](https://wiki.blender.org/wiki/Reference/Release_Notes/2.82/Cycles)).

Максимальная протестированная версия Блендера: 3.4.0-Beta.

В апстриме есть версия для Блендера 2.7. Для экспорта материалов она использует устаревший рендерер `Blender Internal`, который был удалён в Блендере 2.8.

Скачать новейшие версии Блендера: <https://builder.blender.org/download/daily>.

---

[Blender](http://www.blender.org) to [Urho3D](https://urho3d.github.io) mesh exporter.

Guide [here](https://github.com/reattiva/Urho3D-Blender/blob/master/guide.txt).

Installation:
- download the repository zip file        
![download](https://cloud.githubusercontent.com/assets/5704756/26752822/f5ebaecc-4858-11e7-8e7c-35082ee751d3.png)
- menu "File"
- select "User Preferences..."
- select page "Add-ons"
- click "Install from File..."        
![install](https://cloud.githubusercontent.com/assets/5704756/26752823/fd119d7e-4858-11e7-9795-5d3b9d1a895c.png)
- select the downloaded zip file
- enable the addon

The addon is located in the "Properties" panel, at the end of the "Render" page (camera icon):
![location](https://cloud.githubusercontent.com/assets/5704756/26752826/0145c014-4859-11e7-9eb3-15f1724f3d6e.png)
