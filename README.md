<html>
<h1>Сделать нейронную сеть</h1>
  Τατόι
<h2>Сделать нейросеть до 9 раз меньше</h2>
<ul><strong>Сделать нейросеть в 1.5 раза меньше - 1 000$</strong><strong></strong></ul>
<h2>Поднять Test Аccuracy до 99.9% Вашей нейронной сети</h2>
<ul><strong>Поднять Test set accuracy:</strong><br></ul>
<ul>с 84% до 86% - 5000$<br>с 86% до 88% - 20000$ <br>... и так далее <strong>до 99.9%<strong>, к</strong><strong>огда нейросеть лучше, чем человек.</strong><br><br></strong>Ув. HR. Тут написано в 1.5 раза. Вашу нейронку. Это значит, я гарантирую новые технологии лучше, чем в компании. А до 99.9% <strong>test set accuracy </strong>видели? </ul>
<ul>WhatsApp +7926931932два <br>Telegram @shatatoy или +7926931932два <br>vk - shatatoy </ul>
<ul>Жуйков Александр - Татой ( Шататой - Syrius )</ul>
<ul><br>Моделирую и разрабатываю новые нейросети. <br>Направление: <br>Роботы, системы, речь, текст, видео. </ul>
<ul>Разработанные мною технологии позволяют делать <strong>нейронки</strong> и кое что поумнее, <strong>которые на 5 - 10 лет превосходят</strong> любые нейронки большинства компаний. </ul>
<ul>Пример.<br>Примечание 1. Конвертация звука в изображение, а потом распознавание - это техника плохого тона. Даже как дополнительная модель в параллели.<em> Это просто учебник</em>. <br>Примечание 2. Надо продавать дырку, а не сверло (а еще лучше - счастье, игрушку в ярком фантике). Я работаю над этим и предпочитаю продавать массам. Но<strong>. </strong><em>Мне нужна команда</em>. Показываю что есть, больше нет времени отвлекаться.</ul>
<ul>Простое распознавание голосовых команд.<br><br>Итог:
<em><br>Моя Модель1 <strong>в 11 раз меньше</strong> той, что в руководстве (count_params 148,645 против 1,625,611) <strong>и значительно лучше по всем параметрам</strong>. </em></ul>
<ul>Показатели этого руководства на 21.03.2021:<br><a href="https://www.tensorflow.org/tutorials/audio/simple_audio" rel="nofollow">https://www.tensorflow.org/tutorials/audio/simple_audio</a><br>Total params: 1,625,611<br>val_loss: 0.4848 - val_accuracy: 0.8388<br>Test set accuracy: 84%
 
<figure><img src="https://habrastorage.org/getpro/moikrug/uploads/redactor_image/10042021/images/3f23227df73938c84d94fba9a26753cc.png" data-image="ves8qf2blynu"></figure>
 <figure><img src="https://habrastorage.org/getpro/moikrug/uploads/redactor_image/10042021/images/e861cf87a9e5758190f3e23455ddc570.png" data-image="0v6sa48vu1ah"></figure></ul>
<ol><strong><br></strong></ol>
<ul><strong>Модель 1</strong>
<br>собранная автоматически, моим роботом:
<br>count_params 148645
<br>evaluate loss 0.3729 - evaluate accuracy 0.88
<br>Test set accuracy 84.62%<figure><img src="https://habrastorage.org/getpro/moikrug/uploads/redactor_image/10042021/images/0d7a4a95526f6554c3c5ce06ba89d7c0.png" data-image="esjbpdukezjp"></figure>



<br><strong>Модель 2</strong>
<br>Тяжёлая, собрана автоматически, моим роботом
<br>count_params: 3,003,038
<br>evaluate loss: 0.2823 - evaluate accuracy: 0.9087
<br>Test set accuracy: 89.00%<figure><img src="https://habrastorage.org/getpro/moikrug/uploads/redactor_image/10042021/images/5d8a56d35e01de249d867c24873fbcdd.png" data-image="y70k49oheavg"></figure>



<figure><img src="https://habrastorage.org/getpro/moikrug/uploads/redactor_image/10042021/images/b7d35b6fecf284ee52205c4ee9a26cba.png" data-image="gcyqw18htk7r"></figure><br><br>loss - меньше лучше
<br>accuracy, val_accuracy - больше лучше.
<br>Test set accuracy - проверка на данных, которые машина не видела, больше лучше.<br>count_params - это количество параметров нейросети. меньше - очень лучше. </ul>
<ul>Всё те же 6400 тренировочных звуковых файлов / 6400 / 800

<br>Алгоритм универсальный, от 2020/04 и сейчас он другой. Подходит для любых нейронок. Это simple audio пример, наскорую. Это не высший пилотаж.

<br>Алгоритмов у меня много. самых разных. Чаще алгоритмы не для сбора, а для создания особых нейронок, расширенных, универсальных и пр.<br>

<br><strong>Понимание технологий или практиковал, среди прочих:</strong>
<br>• TensorFlow и Keras <br>• Подготовка датасетов, нормализация данных
<br>• Custom Embedding, включая изобретенные авторские технологии
<br>• Замораживания весов и слоев.
<br>• Сохранение - восстановление модели и весов.
<br>• Перенос обучения - Transfer Learning.
<br>• Предобученные сети.
<br>• Custom-слои, модели, Custom-функции активации и метрики.
<br>• Автотюниг, AutoML.
<br>• Регуляризация и Dropout - борьба с переобучением.
<br>• Batch Normalization.
<br>• Маскирование.
<br>• Манипулирования со сложными LR.
<br>• использование в TF 16-битных и 32-битных типов (float16, float32) для ускорения или точности.
<br>• TensorBoard.
<br>и другое.
<br>• Классификация, регрессия, генерация и др.

<br>Понимание технологий 
<br>• RNN, GRU, LSTM, 
<br>• Convolutional NN, 
<br>• Encoding-Decoding, Variational Autoencoders (VAE), 
<br>• Generation - GAN, 
<br>• Seq2seq и Attention, 
<br>• Transformer BERT, GPT-3, 
<br>• ELMo и другое.

<br>Кластеризация:
<br>• K-means
<br>• Affinity Propagation
<br>• Mean Shift
<br>• Spectral clustering
<br>• Hierarchical clustering
<br>• DBSCAN
<br>• OPTICS и другое.</ul>
<ul>Сотни открытий, идей, собственных custom-технологий и направления исследований, ресерчей:

<br>Разработка системы самого Института ИИ и поисков, работ, новейших производств (интеллект).
<br>Разработка систем исследований (особого Института)
<br>Разработчик скоростного образования.
<br>Экспонента для ИИ и х интеллекта ... куда же без неё.
<br>Универсальный, Сильный ИИ (как от реального к реальному, так и Футурология (будущее, идеи без критики).
<br>Обучение без учителя, Unsupervised learning.
<br>Обучение с частичным привлечением учителя, Semi-supervised learning.
<br>Custom Embedding, включая изобретенные авторские технологии.
<br>Технологии и изобретения подачи данных для нейронок, включая "на лету" (видео, текст, звук, речь, документация).
<br>Обучение на неразмеченных данных.
<br>ИИ-самосоздание.
<br>Максимальный автоматизм и самооптимизация.
<br>"Снежный ком" - бесконечное самосовешенствование, обучение. 
<br>Расширенная картина по объекту, сложная нейросеть.
<br>Сложная последовательность, конвеер, цепочка для нейросети.
<br>Модернизировал и изобрел системы регрессий и предсказаний многократно (например робот на Московскую и NY биржи, крипта - всё в прошлом).
<br></ul>
<ul>

Любимые направление - развитие, новые исследования и разработки, масштабный прогресс, цивилизация, новейшие производства, развитие медицины и науки в крупных масштабах.

<br>Системы для AI, мышления, решений, изобретений, производств новейших технологий и продуктов.


<br>Здоровье и продление жизни, поддержка разума, памяти и всех процессов в организме в отличном состоянии, прорывные технологии и продукты.

<br>Разрабатываю для опытов и экспериментов, для сбора и тестов блоков AI.
<br> Разрабатываю системы поддержи командам по AI, помощь в создании и условий для них, советник по работе с AI стартапами, конструктор. </ul>
<ul>
Архитектура компьютеров, компьютерное "железо" - углублённая практика. Мои первые компьютеры задолго до Pentium1 и помешан на материнках, кешах, процах, винтах, памяти и периферии.
<br></ul>
<ul>• Pandas, Numpy.
<br>• цифрового видео, звука, фото - опыт в автоматическом, пакетном редактировании, нарезке, конвертировании и прочее - данные для нейронки.
<br>• Базы данных.
<br>• Опыт предсказания курсов валют, акций, криптовалют.  Корреляции. 
<br>• Успешный маркетмейкер - программист ( в % - сверх-прибыль, роботы и нейросети для безрисковой торговли).



<br>Создание / Программирование:
<br>• Google Colaboratory, Jupyter Notebook и редакторы кода для PC
<br>• сайты, магазины, роботы, сервисы, управление интернет-проектами.
<br>• php, lua, qlua, mySQL, PhpMyAdmin, json, xml, api клиентом, Vk api - (опыт больше 3х лет), сам всё делал, а так же привлекал мастеров, организатор, идея, ведущий проекта, собственные проекты. 
<br>• php OОP, python OОP, WebSocket, JS, - на этом совсем чуть-чуть. 
<br>• Освою любой язык и фреймворк - быстро. 
<br>• Создал роботов-маркетмейкеров на Мосбирже (Quik) и на криптобиржи - опыт больше 3х лет. Это последняя работа, результат - прибыль, шустрые, считают 1000000 комбинаций за минуты на i5, 3 уровня кэша, защиты от шпилек, от глюков внешних API. 
<br>• графики, информеры и калькуляторы - кэш, защиты от шпилек, от перегруза, от роботов, сохранив доступ скрытым роботам поисковиков, обработка потери связи с внешним API, на php-библиотеке, можно на js и чем угодно. 
<br>• Участвовал в руководстве проектами (создание роботов, сайтов для компании, дизайн).
<br>• Bootstrap3, Битрикс, 1С - давно было, опыт меньше года. 
<br>• Опыт работы с клиентом (доверие, личное расположение, могу хорошо зарабатывать, ценит, повторно).

<br>• статистика, Google Analytics, Яндекс.Метрика, LiveInternet, Wordstat.
<br>• Поисковая оптимизация сайтов, сайт 10 лет приносит прибыль без поддержки. Средняя была 2000 уников в день, макс 20000.
<br>• Яндекс.Директ, Google AdWords и в Таргете.
<br>• Рекламная сеть Яндекса, Adsense. 
<br>• CRM (писал CRM себе на php + Вконтакт API).
<br>• Рекламные баннеры.

<br>Интернет - магазин 
<br>• опыт в элитном бутике: новый сайт, фото, видео, net, всё IT, имиджмейкер, дизайнер, портной, мода.
<br>• OpenCart. Автонаполнение, загрузка-выгрузка-парсинг товара с других сайтов, синхронизация с 1C
<br>• любая CMS. </ul>
<ul>Радиотехника, радиоэлектроника, аппаратура - паял, собирал по схемам, ремонтировал.
<br>Автолюбитель, на железе авто помешан, собирал - разбирал авто.

<br>Фото-видеосъемка, графика, видео:
<br>Портретная, с подсветкой, вспышкой, глубиной резкости, без теней, сменными объективами, подвижной платформой и штативом.
<br>• CorelDRAW, Photoshop.
<br>• 3D редакторы.
<br>• Видеоредакторы.
<br>• Дизайн и Веб-дизайн. </ul>
<ul><strong>Звук, озвучка и музыка.
</strong><br>• Cubase. Фрукты. Cakewalk Sonar, Waves, Sound Forge, MIDI и VST плагины - Большой опыт.
<br>• эффект-процессоры, обработка звука, сэмплы и синтезаторы, сведение.

<br>Системы, OS, офис 
<br>• ставил/настраивал Windows, офисные сети и инет Большой опыт.
<br>• Компьютерное железо, ремонт, настройка сети офиса.
<br>• Linux, Ubuntu, Debian, Apache/Nginx/php/http-сервер. 
<br>• Работы по FTP. 

<br>• Английский - 20 лет чтение научной, сложной документации, технической - очень разной, с очень широким охватом. </ul>
<p>Раннее
знакомство с TensorFlow и Keras - позднее я в корне модернизировал и изобрел
системы регрессий и предсказаний многократно.</p>
<p>Регрессия
(не предсказание) курса Биткоина, простая, ни одной корреляции не брал, исходя
только из котировок BTC. Пример графиков выхлопа нейросети</p>
<p><a href="https://kurs-dollara.net/hh/hh1.php" rel="nofollow">https://kurs-dollara.net/hh/hh1.php<br></a>(кликайте
на изображение)</p>
<p>Сайты - работа или основание, 2016г </p>
<ul><a href="http://unsupervise.ru/" rel="nofollow">http://unsupervise.ru/</a>
<br><a href="https://kurs-dollara.net/" rel="nofollow">https://kurs-dollara.net/</a> Писал для себя с 2011г. автоматический, самогенерация, самописный (полигон для экспериментов) пригодилось для идей роботов-ИИ.
<br><a href="http://darneo.net/" rel="nofollow">http://darneo.net/</a> Битрикс
<br><a href="http://terrasnaya-doska.com/" rel="nofollow">http://terrasnaya-doska.com/</a>
 Опенкарт и сайтов 20 еще...
<br><a href="http://www.europa-exclusive.com/" rel="nofollow">http://www.europa-exclusive.com/</a> - основатель первого сайта, 2002г
<br><a href="https://milato.ru/" rel="nofollow">https://milato.ru/</a> - 2018, пока он был в Москве </ul>
<ul>Позитивный, дружественный в коллективе, энтузиаст.
<br> тел: 8919990159два, +796219двa323шeсть, +792066тpи788двa 
<br>WhatsApp +7926931932два 
<br>Telegram @shatatoy или +7926931932два</ul>
<ul>Лучше, если Вы начинаете с "Вы приглашены и утверждены на должность..."
<em><br></em></ul>
<ul><strong>
делать ии - это не шуточное занятие</strong> для мозгов, Ваш звонок должен быть конструктивным, не спамом. Проще говоря - <strong>на работу</strong> сразу.</ul>
<ul>

Это запрос на одну из самых высоких должностей в департаменте (Генеральный директор, Главный конструктор). <br>Внимание: 
 <li>У   меня нет высшего официального образования. </li>
 <li>Нет   опыта работы в должности крупного руководителя. </li>
 <li>Мне   50 лет. </li>
 <li>Место проживания до входа в должность - Смоленск. После возможно - 15 минут   от места работы.</li></ul>
<p>... и тем не менее.</p>

</html>
