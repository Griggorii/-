# -
Linux Readme Fix
Знаки вопроса вместо кириллицы на флешке

Открываем от рут папку /media удаляем всё оттуда и перезагружаемся.

Если в консоли квадратики то sudo -rm rf /etc/kbd && update-initramfs -u


Griggorii создатель OS2.0 | OS3.0 | OS8.0 | OS9.0 |OS11 

Как видите тут не хайпожеры с линуксорг, а решаются настоящие задачи на которые государство не выделят на разработку , а 
все трясется над своими не до осями и только туда даёт.

Кто там завязан и деньги получает от всяких редхат пишите что нужен скрипт -rm -rf /media при загрузке и mkdir этой же директории 
иначе эти фейлы можно ловить при разработке

Так же это поможет если вдруг накопители стали плохо и медленно монтироваться

Почему это приводит к феилу пример: Я создал ядро https://github.com/Griggorii/linux-kernel-5.1.0_amd64.deb и вдруг обнаружил 
что я не могу обновить initrd обычно я делаю бекап из boot initrd ядра в этот раз понадеялся и удалил что бы пресобрать командой 
initramfs-update -u -v и не тут то было в media всё поехало и видимо зациклилось , а надо было полностью чистить что бы не ловить 
мёртвую петлю в программировании какое бы оно не было.

Так же все кто понял меня правильно и понял что я работал по настоящему над системой , просьба пробивать жидовскую науку и выводить на свет правду потому что вы посмотрите со времён етк ничего там особо не менялось и как и обычно все пересоздается линковкой , как 
только я получу мировую успешность вам как журналистам я откину денег ну потому что естественно с мировым признанием моей оси ко мне естественно пойдут вливания на разработку оси которая будет менее раздутой.

Не глупый человек щас знает что интернет обладает более мощной информацией и кто сюда уже смотрел уже давно это знает.
Суть в чём : вы в продакшене и тут бац и спасли за счёт этой статьи от переустановки докера потому что механизм плюс минус 
, но один и тот же вы заработали итд. Посмотрите на сколько мир туп за уязвимости платят миллионы долларов , а вот за такие же 
найденные баги которые аналогично разрушают систему не могут заплатить при чём система тупо может полететь у тех же хакеров 
которые заработали на уязвимости.
Так что найденная информация по сути стоит миллионы долларов , но вот так бесплатно лежит в замороженном состоянии и пока что можно
 даже на этом обойти ошибки в продакшене этих образов итд , так что цените найденный контитул.
