# Coursework Pose-Detection

Данный проект сделан на основе yolov7

Ссылка на оригинальный репозиторий

https://github.com/WongKinYiu/yolov7

Данный проект позволяет определять положение кистей и стоп на видео, обработанном медианным фильтром

## Запуск
Переместите нужное видео в папку yolo/input

Через cmd запустите команду 

```
python detect.py --weights weights\best.pt --conf {confidence} --source input\{filename} --view-img
```
Здесь confidence - это число в интервале от 0 до 1, рекомендуемое значение 0.5-0.6

Параметр filename - имя исходного файла

Результат будет находиться в папке yolo/runs/detect
