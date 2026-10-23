---
title: Kepta — политика конфиденциальности / Privacy Policy
lang: ru
---

<!--
  Текст к публикации владельцем (решение владельца 22 октября 2026, K6). Описывает поведение приложения на 23 октября 2026
  (версия телефона на Kotlin): что хранится, что и куда уходит, какие разрешения и зачем. Для GitHub Pages файл кладётся в
  публичный репозиторий как `index.md` — заголовок выше Jekyll понимает сам. Опубликовано владельцем 23 октября 2026:
  https://1dwqqqad.github.io/kepta.github.io/ — адрес записан в ресурс `about_privacy_url`, и строка «Конфиденциальность» в
  настройках ведёт туда. Перед публикацией вписать дату в строку «Действует с». Всякая перемена в поведении приложения,
  о которой здесь сказано, — правка этой страницы в тот же день и новая публикация (23 октября 2026: файл Kepta без места).
-->

# Kepta — политика конфиденциальности

**Действует с:** 23 октября 2026
**Разработчик:** Aleksei Vlasov
**Почта для вопросов:** [keptatodo@gmail.com](mailto:keptatodo@gmail.com)

Kepta — приложение для быстрых записей: задач, заметок и списков. Эта страница описывает, какие данные приложение
хранит, что и кому оно передаёт и как это остановить.

## Где хранятся ваши данные

Всё, что вы записываете в Kepta, — записи, папки, проекты, настройки, приложенные снимки и звук голосовых записей —
хранится **только на вашем телефоне**, в закрытой папке приложения. Учётной записи в Kepta нет, и на свой сервер приложение
ничего не отправляет. Резервное копирование Android для Kepta выключено: данные приложения не копируются в облако Google.

Удаление приложения или очистка его данных в настройках Android стирает всё, что Kepta хранит.

## Что уходит из телефона и кому

### Голосовой ввод — только когда вы им пользуетесь

Чтобы превратить речь в запись, Kepta использует два сервиса:

1. **Deepgram** (deepgram.com) — распознавание речи. Приложение отправляет **запись вашего голоса** и подсказку языка;
   в ответ приходит текст.
2. **OpenAI** (openai.com) — разбор сказанного: дата, время, напоминания, повтор, подпункты. Приложение отправляет
   **распознанный текст**, **текущие дату, время и часовой пояс телефона** и **названия ваших папок и проектов** (чтобы
   сказанное «в папку Дом» нашло вашу папку); в ответ приходит разобранная запись.

Оба сервиса находятся за пределами России (в США) и обрабатывают переданное по своим правилам. Если голосовым вводом не
пользоваться, ничего из этого не отправляется. Без сети запись ждёт на телефоне и отправляется, когда сеть появится.

### Отправка записи другому человеку — только по вашей команде

Когда вы выбираете «Поделиться», запись уходит в то приложение, которое вы выберете, — текстом или файлом Kepta. Файл
Kepta несёт копию записи без обсуждения, соавторов, места, снимков и звука. Полученный файл Kepta добавляется к вам только после
вашего подтверждения.

### Больше никуда

Kepta не содержит рекламы, систем аналитики и отслеживания и не продаёт и не передаёт ваши данные никому, кроме сказанного
выше.

## Разрешения и зачем они нужны

- **Микрофон** — записывать голос для голосового ввода. Спрашивается при первой записи.
- **Уведомления, точные будильники, запуск после перезагрузки** — напоминать о записях вовремя.
- **Местоположение (приблизительное)** — только когда вы прикрепляете к записи место. Место хранится в записи на
  телефоне; открывая его, Kepta передаёт координаты выбранному вами приложению карт.
- **Календарь (чтение)** — только когда вы переносите события из календаря телефона в Kepta. Kepta в календарь ничего
  не пишет.
- **Интернет и состояние сети** — для голосового ввода (см. выше).

Снимки приложение получает через приложение камеры или выбор файла и хранит у себя; к приложенным файлам оно держит
только ссылку и право их открыть.

## Экран блокировки и виджеты

Карточка ближайшей записи на экране блокировки и виджеты показывают ваши записи. Текст записей на экране блокировки
можно скрыть в настройках («Экран блокировки» → «Текст записей»). Записывать с экрана блокировки без разблокировки можно,
только если вы это разрешили («Запись без разблокировки»).

## Дети

Kepta не предназначено специально для детей и не собирает сведений о возрасте.

## Изменения

Если поведение приложения изменится так, что это касается сказанного здесь, эта страница обновится, а дата в её начале
сменится.

## Связь

Вопросы и просьбы — на [keptatodo@gmail.com](mailto:keptatodo@gmail.com).

---

# Kepta — Privacy Policy

**Effective:** October 23, 2026
**Developer:** Aleksei Vlasov
**Contact:** [keptatodo@gmail.com](mailto:keptatodo@gmail.com)

Kepta is an app for quick capture of tasks, notes and lists. This page explains what data the app stores, what it sends
and to whom, and how to stop it.

## Where your data is stored

Everything you put into Kepta — records, folders, projects, settings, attached photos and the audio of voice records — is
stored **only on your phone**, in the app's private storage. Kepta has no accounts and sends nothing to a server of its
own. Android backup is turned off for Kepta: its data is not copied to Google's cloud.

Uninstalling the app or clearing its data in Android settings erases everything Kepta stores.

## What leaves the phone, and to whom

### Voice input — only when you use it

To turn speech into a record, Kepta uses two services:

1. **Deepgram** (deepgram.com) — speech recognition. The app sends **the recording of your voice** and a language hint and
   receives the text.
2. **OpenAI** (openai.com) — understanding what was said: date, time, reminders, repeat, subtasks. The app sends **the
   recognized text**, **the phone's current date, time and time zone** and **the names of your folders and projects** (so
   that "to the Home folder" finds your folder) and receives the parsed record.

Both services are outside Russia (in the USA) and process the data under their own terms. If you don't use voice input,
none of this is sent. Without a connection, a recording waits on the phone and is sent when the connection returns.

### Sending a record to another person — only on your command

When you choose "Share", the record goes to the app you pick — as text or as a Kepta file. A Kepta file carries a copy of
the record without comments, collaborators, location, photos or audio. A received Kepta file is added only after you confirm.

### Nowhere else

Kepta has no ads, analytics or tracking, and does not sell or pass your data to anyone beyond what is described above.

## Permissions and why

- **Microphone** — to record your voice for voice input. Asked at the first recording.
- **Notifications, exact alarms, start after reboot** — to remind you on time.
- **Location (approximate)** — only when you attach a place to a record. The place is stored in the record on the phone;
  opening it passes the coordinates to the maps app you choose.
- **Calendar (read)** — only when you import events from the phone's calendar into Kepta. Kepta writes nothing to the
  calendar.
- **Internet and network state** — for voice input (see above).

Photos come from the camera app or the file picker and are stored by the app; for attached files, the app keeps only a
link and the right to open them.

## Lock screen and widgets

The nearest-record card on the lock screen and the widgets show your records. Text on the lock screen can be hidden in
settings ("Lock screen" → "Entry text"). Capturing from the lock screen without unlocking works only if you have allowed it
("Capture without unlocking").

## Children

Kepta is not directed at children and does not collect age information.

## Changes

If the app's behaviour changes in a way that affects what is said here, this page will be updated and the date at its top
will change.

## Contact

Questions and requests: [keptatodo@gmail.com](mailto:keptatodo@gmail.com).
