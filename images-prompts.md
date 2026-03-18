# images-prompts.md — Промпты для изображений акций МедСпринт

**Дата:** 18.03.2026
**Назначение:** Фоновые изображения для карточек акций на medsprint.ru/actions/

---

## Технические параметры

- **Формат:** 3:2 (горизонтальный, под карточки сайта)
- **Инструменты:** Midjourney (`--ar 3:2`), DALL-E 3, Flux
- **Важно:** На изображение накладывается цветной оверлей (синий, как на текущих карточках) — поэтому сами фото не обязаны быть тёмными, главное — не слишком пёстрый центр
- **Стиль:** реалистичная фотография, профессиональная, без текста в кадре, без стетоскопов и шприцев крупным планом (клише)

---

## Акция 1: Готовый сайт + AI-продавец

**Концепция:** AI-продавец как инструмент конверсии — не просто чат, а запись к врачу в один клик. Показываем сайт клиники с активным AI-интерфейсом записи: пациент пишет вопрос, бот предлагает выбрать врача и время.

**Промпт (Midjourney/DALL-E 3):**
```
Modern laptop screen showing a clean medical clinic website with an AI booking assistant interface,
appointment scheduling chat popup with calendar widget, blue glowing interface,
soft bokeh background of a clinic reception area,
professional photography, cinematic lighting, no text visible, --ar 3:2 --style raw
```

**Альтернатива (более абстрактная):**
```
Futuristic AI sales assistant interface with medical calendar and appointment icons,
floating chat bubbles with checkmark confirmations,
dark blue gradient background, digital light particles, no people,
clean tech aesthetic, --ar 3:2 --style raw
```

**Что убрать из результата:** если нейросеть добавила текст в кадр — регенерировать или убрать в редакторе.

---

## Акция 2: Копирайтинг + публикация в издании

**Концепция:** Создание экспертного контента. Врач или специалист за работой над текстом — профессиональная публикация как результат.

**Промпт:**
```
Medical professional typing on laptop in modern office, medical reference books in background,
warm professional lighting, shallow depth of field, focus on hands and keyboard,
no text visible on screen, dark vignette edges, editorial photography style, --ar 3:2 --style raw
```

**Альтернатива:**
```
Open medical journal magazine on desk next to laptop, professional office environment,
natural window light, clean minimalist composition, no text visible,
top-down flat lay perspective, --ar 3:2 --style raw
```

---

## Акция 3: SEO-продвижение + SEO-аудит сайта

**Концепция:** Диагностика сайта — как рентген. Специалист видит конкретные проблемы и точки роста. Центральный образ: экран с аналитикой сайта, цифры позиций, технические показатели.

**Промпт:**
```
Business professional reviewing website SEO audit report on large monitor,
performance metrics and health score dashboard visible on screen,
dark modern office environment, blue and teal color scheme,
screen glow illuminating the scene, no recognizable logos or text,
professional business photography, --ar 3:2 --style raw
```

**Альтернатива:**
```
Close-up of website analytics dashboard showing site health metrics,
search ranking positions chart, technical audit results on screen,
blue ambient office lighting, shallow depth of field, no text visible, --ar 3:2 --style raw
```

---

## Акция 4: Быстрое SEO — 7-дневный тест-драйв

**Концепция:** Скорость и результат. Ракета или стрела вверх. Или: поисковая строка с позициями в топе.

**Промпт (скорость/рост):**
```
Abstract rocket launching upward through digital data streams,
dark deep blue background, dynamic motion blur, futuristic technology aesthetic,
vibrant electric blue and white colors, no text, cinematic composition, --ar 3:2 --style raw
```

**Альтернатива (реалистичная):**
```
Close-up of person's hands on keyboard with browser showing high search engine rankings on screen,
dark blue office atmosphere, soft focus background,
professional business setting, no recognizable logos, --ar 3:2 --style raw
```

**Рекомендую:** второй вариант лучше сочетается с реалистичным стилем остальных карточек.

---

## Акция 5: Яндекс.Директ + аудит рекламы или аналитики

**Концепция:** Деньги на рекламу — и полная прозрачность куда они идут. Воронка, дашборд, показатели кампаний или аналитики.

**Промпт:**
```
Marketing funnel visualization on large monitor in dark office,
conversion analytics and performance metrics displayed,
blue and orange accent colors on dark background,
business professional environment, no text visible, cinematic lighting, --ar 3:2 --style raw
```

**Альтернатива:**
```
Business analyst reviewing advertising performance dashboard on screen,
modern dark office, blue screen glow, data visualization charts visible,
professional corporate photography, no recognizable UI elements, --ar 3:2 --style raw
```

---

## Акция 6: SMM + аудит аккаунтов или оформление профиля

**Концепция:** Анализ присутствия клиники в соцсетях или создание нового профиля с нуля. Показываем не "лайки", а профессиональный медицинский аккаунт — чистый, структурированный, с реальной аудиторией.

**Промпт:**
```
Marketing specialist reviewing social media profile analytics on laptop screen,
engagement metrics and follower growth charts visible,
modern bright office, smartphone with social media app in foreground,
professional yet approachable atmosphere, no text visible, --ar 3:2 --style raw
```

**Альтернатива:**
```
Clean professional social media profile on smartphone screen,
medical clinic branding visible, modern minimal design,
soft bokeh office background, blue and white color scheme,
natural light, no text legible, --ar 3:2 --style raw
```

---

## Общие советы по генерации

### Единый стиль для всех 6 изображений
Чтобы карточки выглядели как серия, добавьте в конец каждого промпта общий стилевой хвост:
```
professional corporate photography, blue color palette, cinematic lighting,
no text, photorealistic, --ar 3:2 --style raw --v 6
```

### Если DALL-E 3 (через ChatGPT)
Добавьте в начало каждого промпта:
```
Photorealistic professional photograph, no text in image:
[остальной промпт]
```

### Тёмный оверлей
Если итоговые фото слишком светлые для читаемости текста — в Canva/Figma/Photoshop добавьте поверх прозрачный синий прямоугольник с opacity 40-60%. Это тот же эффект, что на текущих карточках сайта.

### Что регенерировать
- Появился текст в кадре → перегенерировать с добавлением `absolutely no text, no writing`
- Слишком клишированно (шприц, стетоскоп) → добавить `no medical equipment close-ups, no syringes, no stethoscopes`
- Нереалистично/мультяшно → добавить `photorealistic, real photography style, --style raw`
