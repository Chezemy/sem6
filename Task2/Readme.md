<p>Можно взять готовые нейросети или обучить самому</p>
<p>Обучение нейросети состоит из:</p>
<ul>
  <li>обучение
  <li>тренировка - загрузка датасета и выявление уравнения
  <li>тест - загрузка 
 </ul>
 
<p>flags.DEFINE_string('framework', 'tf', '(tf, tflite, trt')</p>
<p>flags.DEFINE_string('video', './data/video/test.mp4', 'path to input video or set to 0 for webcam')</p>
<p>python object_tracker.py --video 0 --output ./outputs/demo.avi --model yolov4</p>
<p>аргументы командной строки def main(_argv): Первое из скобок - framework название флага</p>
<p>все остальное - это какие значения принимает флаг</p>

 
 
