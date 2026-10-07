
## Одностраничный сайт-визитка для тренера по йоге и пилатесу. 


<img width="2560" height="1280" alt="cover" src="https://github.com/user-attachments/assets/47da647a-301f-4ffd-aa47-8f39a37f9d29" />


## Стек технологий

### Разметка — HTML5
### Стили — CSS3 (без препроцессоров и фреймворков)
### Скрипты — JavaScript + jQuery 3.7.1
### Слайдеры — Swiper 11.1.4
### Шрифты — Google Fonts
- **Literata** — вариативный шрифт с оптическим размером (`opsz`) для заголовков и цитат
- **Onest** — современный гротеск с отличной кириллицей для текста и интерфейса

<img width="3200" height="2000" alt="mockups" src="https://github.com/user-attachments/assets/2f555c71-cb88-497c-ae6b-313e405dc013" />


### SEO
- `title`, `description`, `keywords`, `robots`
- `canonical`, `hreflang`, `theme-color`
- **Open Graph** (тип `profile`) и **Twitter Card** с обложкой 1200×630
- `robots.txt` и `sitemap.xml` 
- `site.webmanifest`
- `alt` у всех изображений, иерархия заголовков H1 → H3

### Микроразметка — Schema.org (JSON-LD, `@graph`)
- `WebSite` и `WebPage`
- `Person` — имя, должность,
- `ProfessionalService` — зона обслуживания «онлайн», контакты
- `VideoObject` — видео-визитка с превью и длительностью
- `FAQPage` — шесть вопросов и ответов для расширенных сниппетов

### GEO (Generative Engine Optimization)
- **`llms.txt`** — краткое машиночитаемое описание тренера и услуг для LLM-поисковиков GOOGLE YANDEX
- В `robots.txt` явно разрешены GPTBot, ClaudeBot, PerplexityBot и YandexBot
- FAQ и Speakable-разметка формулируют ответы так, чтобы их было удобно цитировать ИИ-ассистентам

### Производительность
- Фото конвертированы в **WebP**

- Видео перекодированы через **FFmpeg**
- `preload` и `fetchpriority="high"`, `loading="lazy"` и `decoding="async"` 

## Дизайн

| Токен | Цвет | Где используется |
|-------|------|------------------|
| Mist | `#EEF2F0` | фон страницы, «байкальский туман» |
| Ink | `#232A2E` | текст, основные кнопки |
| Mint | `#7FCDB9` | акцент, взят с мяча на фотографиях |
| Mint deep | `#3E9C86` | иконки, ссылки, пагинация |
| Mint pale | `#DCF1EA` | плашки, иконки-«таблетки» |
| Cedar | `#1F3329` | тёмная тайга, логотип |
| Slate | `#363F43` | фон блоков с фото, снят со снимка |

<img width="3200" height="2580" alt="design-system" src="https://github.com/user-attachments/assets/4514f8b2-50cf-4f7b-86a0-58380e7304fd" />


