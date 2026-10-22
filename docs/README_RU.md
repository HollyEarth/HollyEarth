<div align="center">

# HOLLYEARTH

### ОДНА СИСТЕМА. МНОГО МИРОВ.

**Город · Политика · Спорт · Социальная сфера · Расследования · Аналитика · Опыт**

Реальные места, публичные записи, источники, доказательства и открытые вопросы — как одна система. Начинаем с Риги, Латвия.

`v0.1.0` · пилотный исследовательский проект · только документация и медиа · не open source

[English](../README.md) · **Русский** · [Latviešu](README_LV.md) · **[Визуальный атлас →](GALLERY.md)**

</div>

**УЗНАЙ СВОЙ ГОРОД. ПРОСЛЕДИ ИСТОЧНИК. ИССЛЕДУЙ НОВЫЕ МИРЫ.**

От улиц Риги до масштаба всей планеты — развивающаяся вселенная мест, общественно значимой информации, пространственных впечатлений и открытых вопросов.

<sub>Настоящий скриншот v0.1.0. Riga Twin: слои районов, спорта и социальных услуг на фотореалистичной 3D-модели Риги. Метки «Wellbeing» помечены DEMO.</sub>

---

## Одна система. Много миров.

![HollyEarth — THE UNIVERSE](../media/infographics/overview.svg)

*Авторская концептуальная инфографика — визуальная метафора, не скриншот продукта.*

**Начните с вопроса, а не с таблицы.** Что происходит в моём районе? Что на самом деле написано в решении думы? Где занимается спортивный клуб? HollyEarth превращает разрозненные публичные сведения в места, которые можно исследовать, источники, которые можно проверить, и истории, за которыми можно следовать. Сейчас это **частный исследовательский пилот**, а не общедоступный онлайн-сервис.

HollyEarth — AI-native платформа пространственной, городской и исследовательской аналитики. Она объединяет город, его учреждения и организации, политические решения, публичные деньги, социальные услуги, спорт, документы, источники и доказательства — и позволяет исследовать их на карте, как граф, как расследование или как рассказ.

**Реальность → Доказательства → Аналитика → Опыт → Действие** — то, что публикуют регистры, дума, федерации и архивы; хранится вместе с источником, цитатой, статусом и пробелами; связывается в дела, анализ и открытые вопросы; предстаёт как 3D-город, спортивный город, карта социальных услуг, рабочие пространства дел и рассказы с озвучкой. *«Действие» — это `FUTURE`: в v0.1.0 система ничего не записывает обратно в мир.*

> **Видение и сегодняшний день разделены.**
> Цель — одна связанная модель города. **Сегодня HollyEarth — один продукт над несколькими связанными моделями данных, а не единый граф реальности.** Политика и спорт лежат в одном каноническом графе, но пока не связаны между собой; у реестра социальных услуг своя модель; у каждого расследования свой граф доказательств; Riga Twin показывает несколько этих моделей на одной карте. Подробнее: [ARCHITECTURE.md](../ARCHITECTURE.md).

| Мир | Что это | Статус | Галерея |
|---|---|---|---|
| **Город — Riga Twin** | Рига в 3D: слои районов, думы, спорта и социальных услуг | `WORKING` | [Riga Twin](gallery/RIGA_TWIN.md) |
| **Политика** | Рижская дума: заседания, решения, депутаты, партии, выборы, бюджет, доказательства — и интегральное исследовательское пространство | `BETA` | [Политика](gallery/POLITICS.md) |
| **Спорт — HollySport** | Клубы, спортсмены, события и площадки Латвии по данным федераций и протоколов; спортивный город в игровой стилистике | `WORKING` · игровой слой `DEMO` | [HollySport](gallery/HOLLYSPORT.md) |
| **Социальная сфера — Social Intelligence** | Зарегистрированные социальные услуги Риги на интерактивной сцене города | `SHOWCASE_READY` | [Social](gallery/SOCIAL.md) |
| **Расследования** | Дела, построенные из документов: утверждения, источники, цитаты, деньги по типам, открытые вопросы | `WORKING` | [Расследования](gallery/INVESTIGATION.md) |
| **Аналитика** | Детерминированный анализ, Holly, мониторинг, рассуждения модели — по желанию | `BETA` | [Holly AI](gallery/HOLLY_AI.md) · [Мониторинг](gallery/MONITORING.md) |
| **Опыт** | Story на трёх языках, паспорта, досье; Holly Eye — сторонний 3D-глобус с живыми слоями данных мира | `WORKING` · Holly Eye `BETA` | [Story](gallery/HOLLY_AI.md#story) · [Holly Eye](gallery/HOLLY_EYE.md) |

Статусы: `SHOWCASE_READY` · `WORKING` · `BETA` · `PROTOTYPE` · `DEMO` · `RESEARCH` · `FUTURE` — каждая функция в **[FEATURE_STATUS.md](FEATURE_STATUS.md)**. Все экраны продукта с метками статусов: **[визуальный атлас HollyEarth](GALLERY.md)**. Галереи и подробные документы — на английском.

---

## Город

![HollyEarth — CITY](../media/infographics/city.svg)

*Авторская концептуальная инфографика — визуальная метафора, не скриншот продукта.*

**Город — больше, чем карта.** Рига становится пространством, в котором места, учреждения и публичные записи обретают контекст. Начните с города — и перейдите к первоисточнику, когда возникнет вопрос.

**Riga Twin** — общая 3D-карта: 58 районов, 428 решений думы с адресом, 14 спортивных территорий, выделенных городом, 177 зданий социальных услуг, новости районов, панель думы и переходы во все остальные миры. `WORKING`; режим исследования и слой AQAL — `PROTOTYPE`; Wellbeing — `DEMO`.

<table>
<tr>
<td width="33%"><a href="../media/gallery/twin/01-default-council.webp"><img src="../media/gallery/twin/01-default-council.webp" alt="Twin с панелью думы"></a><br><sub>Панель думы рядом с городом</sub></td>
<td width="33%"><a href="../media/gallery/twin/03-layer-council-decisions.webp"><img src="../media/gallery/twin/03-layer-council-decisions.webp" alt="Слой решений думы"></a><br><sub>Решения думы по районам</sub></td>
<td width="33%"><a href="../media/gallery/twin/17-aqal-overlay.webp"><img src="../media/gallery/twin/17-aqal-overlay.webp" alt="Слой AQAL"></a><br><sub>Слой AQAL — `PROTOTYPE`</sub></td>
</tr>
</table>

Пока нет: общей идентичности мест между доменами; дел на карте; режима исследования, который отвечает на вопросы. → **[Галерея Riga Twin](gallery/RIGA_TWIN.md)** · [twin.md](twin.md)

---

## Политика

![HollyEarth — POLITICS](../media/infographics/politics.svg)

*Авторская концептуальная инфографика — визуальная метафора, не скриншот продукта.*

**У каждого решения есть история.** От заголовков — к официальным заседаниям, решениям, голосованиям и документам. Без подмены фактов автоматическими политическими оценками.

**Political Holly OS** — двенадцать модулей над данными Рижской думы: 175 заседаний, 456 решений, 113 депутатов, 7 партий, официальные итоги выборов 2025 года, муниципальные расходы и реестр доказательств. Модули — от `WORKING` (Network, Deputies, Parties & Power) через `BETA` до `DEMO` (District Impact, Smart City Lenses) и `RESEARCH` (Integral City).

<a href="../media/gallery/politics/01-political-os.webp"><img src="../media/gallery/politics/01-political-os.webp" alt="Political Holly OS" width="100%"></a>

**Integral Political Workspace** — восемь исследовательских представлений одних и тех же канонических записей, `PROTOTYPE`: Political Archipelago · Focus Orbit · Evidence & Influence Flow · Holarchic Observatory · Integral Lens Field · Living City Torus · Geo / Twin Bridge · Relationship Graph.

<table>
<tr>
<td width="33%"><a href="../media/gallery/workspace/01-political-archipelago.webp"><img src="../media/gallery/workspace/01-political-archipelago.webp" alt="Political Archipelago"></a><br><sub>Political Archipelago</sub></td>
<td width="33%"><a href="../media/gallery/workspace/02b-focus-orbit-selected.webp"><img src="../media/gallery/workspace/02b-focus-orbit-selected.webp" alt="Focus Orbit"></a><br><sub>Focus Orbit</sub></td>
<td width="33%"><a href="../media/gallery/workspace/03-evidence-influence-flow.webp"><img src="../media/gallery/workspace/03-evidence-influence-flow.webp" alt="Evidence and Influence Flow"></a><br><sub>Evidence &amp; Influence Flow</sub></td>
</tr>
<tr>
<td width="33%"><a href="../media/gallery/workspace/04-holarchic-observatory.webp"><img src="../media/gallery/workspace/04-holarchic-observatory.webp" alt="Holarchic Observatory"></a><br><sub>Holarchic Observatory</sub></td>
<td width="33%"><a href="../media/gallery/workspace/05-integral-lens-field.webp"><img src="../media/gallery/workspace/05-integral-lens-field.webp" alt="Integral Lens Field"></a><br><sub>Integral Lens Field</sub></td>
<td width="33%"><a href="../media/gallery/workspace/06-living-city-torus.webp"><img src="../media/gallery/workspace/06-living-city-torus.webp" alt="Living City Torus"></a><br><sub>Living City Torus</sub></td>
</tr>
</table>

Данные настоящие и с источниками; у нескольких модулей есть известные пробелы (строки бюджета не импортированы, данные заседаний — по июль 2026), а над большинством модулей показан помеченный демо-проект анализа. → **[Галерея политики](gallery/POLITICS.md)** · [politics.md](politics.md)

---

## Спорт

![HollyEarth — SPORT](../media/infographics/sport.svg)

*Авторская концептуальная инфографика — визуальная метафора, не скриншот продукта.*

**За каждым результатом стоят люди и сообщества.** Клубы, площадки, соревнования и спортсмены представлены как связанные профили на основе открытых архивов. Игровой слой — `DEMO`, инструменты организаторов пока прототипы.

**HollySport** — **18 143 спортсмена · 227 событий · 1 326 боёв · 8 401 место в протоколах · 297 клубов и федераций · 133 площадки** по данным реестров федераций, официальных протоколов и публичных архивов; результаты несовершеннолетних не хранятся. Паспорта — `WORKING` / `SHOWCASE_READY`; City Game — `DEMO`; Event OS и Creator — `PROTOTYPE`; экономика MetaSport — `FUTURE`.

<a href="../media/screenshots/07-hollysport-city.png"><img src="../media/screenshots/07-hollysport-city.png" alt="HollySport City" width="100%"></a>

<table>
<tr>
<td width="33%"><a href="../media/screenshots/08-club-passport.png"><img src="../media/screenshots/08-club-passport.png" alt="Паспорт клуба"></a><br><sub>Паспорт клуба</sub></td>
<td width="33%"><a href="../media/gallery/sport/12-athlete-passport.webp"><img src="../media/gallery/sport/12-athlete-passport.webp" alt="Паспорт спортсмена"></a><br><sub>Паспорт спортсмена</sub></td>
<td width="33%"><a href="../media/gallery/sport/15-event-results.webp"><img src="../media/gallery/sport/15-event-results.webp" alt="Результаты события"></a><br><sub>Результаты события — только взрослые</sub></td>
</tr>
<tr>
<td width="33%"><a href="../media/gallery/sport/19-sport-graph.webp"><img src="../media/gallery/sport/19-sport-graph.webp" alt="Граф спорта"></a><br><sub>Граф спорта</sub></td>
<td width="33%"><a href="../media/screenshots/16-hollysport-missions-demo.png"><img src="../media/screenshots/16-hollysport-missions-demo.png" alt="Миссии — демо"></a><br><sub>Миссии — `DEMO`</sub></td>
<td width="33%"><a href="../media/gallery/sport/25-wallet-preview.webp"><img src="../media/gallery/sport/25-wallet-preview.webp" alt="Кошелёк — превью"></a><br><sub>Кошелёк — превью `FUTURE`</sub></td>
</tr>
</table>

Игровой и экономический слои показывают, куда развивается платформа; это не работающие коммерческие сервисы. Event OS — прототип планирования, а не сервис регистрации мероприятий. → **[Галерея HollySport](gallery/HOLLYSPORT.md)** · [sport.md](sport.md)

---

## Социальная сфера

![HollyEarth — SOCIAL](../media/infographics/social.svg)

*Авторская концептуальная инфографика — визуальная метафора, не скриншот продукта.*

**Услуга в реестре не означает, что человек её получил.** Исследуйте зарегистрированные организации, изучайте досье и смотрите, чего публичные данные пока не говорят о доступности, выплатах и результатах.

**Social Intelligence** — социальные услуги Риги по официальному реестру Министерства благосостояния (срез 14 сентября 2026): **256 услуг · 106 поставщиков · 177 зданий · 28 услуг на дому.** `SHOWCASE_READY`.

<a href="../media/screenshots/10-social-stage.png"><img src="../media/screenshots/10-social-stage.png" alt="Social Intelligence" width="100%"></a>

<table>
<tr>
<td width="33%"><a href="../media/screenshots/11-social-dossier.png"><img src="../media/screenshots/11-social-dossier.png" alt="Досье услуги"></a><br><sub>Досье услуги — что неизвестно</sub></td>
<td width="33%"><a href="../media/gallery/social/05-holly-sees.webp"><img src="../media/gallery/social/05-holly-sees.webp" alt="Holly видит"></a><br><sub>«Holly видит» — счётчики реестра, а не оценка</sub></td>
<td width="33%"><a href="../media/gallery/social/06-agreements.webp"><img src="../media/gallery/social/06-agreements.webp" alt="Договоры делегирования"></a><br><sub>Договоры делегирования</sub></td>
</tr>
</table>

**Зарегистрировано ≠ оказано · неизвестно ≠ ноль.** Число получателей, фактические выплаты и качество неизвестны для всех 256 услуг и показаны как неизвестные. Поставщики пока не связаны с основным графом. → **[Галерея социальной сферы](gallery/SOCIAL.md)** · [social.md](social.md)

---

## Расследования

![HollyEarth — INVESTIGATION](../media/infographics/investigation.svg)

*Авторская концептуальная инфографика — визуальная метафора, не скриншот продукта.*

**Не только вывод — весь путь к нему.** Дело объединяет цитаты, документы, типы денежных сумм и открытые вопросы в исследование, по которому можно перемещаться.

Дело собирает решение думы, закупку или организацию вместе с источниками, точными цитатами, утверждениями, деньгами по типам, открытыми вопросами и путём, который прошло расследование. В v0.1.0 — 9 дел.

<a href="../media/screenshots/03-case-overview.png"><img src="../media/screenshots/03-case-overview.png" alt="Обзор дела" width="100%"></a>

<table>
<tr>
<td width="25%"><a href="../media/gallery/investigation/01-case-gallery.webp"><img src="../media/gallery/investigation/01-case-gallery.webp" alt="Галерея дел"></a><br><sub>Галерея дел</sub></td>
<td width="25%"><a href="../media/screenshots/04-evidence.png"><img src="../media/screenshots/04-evidence.png" alt="Путь суммы"></a><br><sub>Откуда взялась сумма</sub></td>
<td width="25%"><a href="../media/screenshots/05-roadmap.png"><img src="../media/screenshots/05-roadmap.png" alt="Ход расследования"></a><br><sub>Ход расследования</sub></td>
<td width="25%"><a href="../media/gallery/investigation/06-kbs-explore.webp"><img src="../media/gallery/investigation/06-kbs-explore.webp" alt="Дело спортивного клуба"></a><br><sub>Дело спортивного клуба</sub></td>
</tr>
</table>

**Утверждение ≠ проверенный факт.** Все 111 утверждений в делах имеют статус «заявлено», у каждого есть источник и цитата; «подтверждено» означает «прямо подтверждено цитатой»; человеком не проверено ни одно. **Запланировано ≠ выплачено:** деньги разделены по типам и никогда не складываются между типами; в делах и в социальной сфере нет записей о платежах. → **[Галерея расследований](gallery/INVESTIGATION.md)** · [cases.md](cases.md)

---

## Аналитика

![HollyEarth — INTELLIGENCE](../media/infographics/intelligence.svg)

*Авторская концептуальная инфографика — визуальная метафора, не скриншот продукта.*

**ИИ должен помогать задавать вопросы, а не изображать всезнание.** HollyEarth объединяет проверяемые записи, детерминированный анализ и необязательные гипотезы моделей. В v0.1.0 Holly работает в контексте конкретного дела, а не как автономный помощник для всего.

HollyEarth работает без языковой модели. Holly — это детерминированные помощники и ассистент внутри дела; рассуждения модели — по желанию и всегда помечены как гипотезы. Мониторинг следит за официальными источниками дел — проверки запускаются вручную, автоматического расписания пока нет. Глобального ассистента и автономных агентов в v0.1.0 нет.

<table>
<tr>
<td width="50%"><a href="../media/gallery/holly/01-analysis-model-hypotheses.webp"><img src="../media/gallery/holly/01-analysis-model-hypotheses.webp" alt="Анализ и рассуждения модели"></a><br><sub>Детерминированный анализ рядом с гипотезами, <b>сгенерированными моделью</b> — `BETA`</sub></td>
<td width="50%"><a href="../media/screenshots/18-monitoring.png"><img src="../media/screenshots/18-monitoring.png" alt="Мониторинг"></a><br><sub>Мониторинг: 18 наблюдений, 26 запусков — `BETA`</sub></td>
</tr>
</table>

→ **[Галерея Holly AI](gallery/HOLLY_AI.md)** · **[Галерея мониторинга и Observatory](gallery/MONITORING.md)** · [holly-ai.md](holly-ai.md) · [monitoring.md](monitoring.md)

---

## Опыт

![HollyEarth — EXPERIENCE](../media/infographics/experience.svg)

*Авторская концептуальная инфографика — визуальная метафора, не скриншот продукта.*

**Информация оживает, когда её можно пережить.** Перемещайтесь между городом, документированным делом и историей на трёх языках. Holly Eye расширяет масштаб до планеты как честно обозначенная **сторонняя интеграция**.

<table>
<tr>
<td width="33%"><a href="../media/screenshots/06-story.png"><img src="../media/screenshots/06-story.png" alt="Story"></a><br><sub><b>Story</b> — дело, рассказанное главами на RU / LV / EN и собранное из его записей. `WORKING`</sub></td>
<td width="33%"><a href="../media/gallery/holly/04-story-versions.webp"><img src="../media/gallery/holly/04-story-versions.webp" alt="Версии и голоса Story"></a><br><sub><b>Версии и голоса</b> — локальный, облачный (с подтверждением) или голос браузера. `BETA`</sub></td>
<td width="33%"><a href="../media/gallery/holly-eye/01-planet-europe-3d.webp"><img src="../media/gallery/holly-eye/01-planet-europe-3d.webp" alt="Глобус Holly Eye"></a><br><sub><b>Мир — Holly Eye</b> — 3D-глобус с живыми публичными слоями данных. <b>Сторонняя интеграция</b> (God's Eye View, автор Bilawal Sidhu), не технология HollyEarth. `BETA`</sub></td>
</tr>
<tr>
<td width="33%"><a href="../media/gallery/holly-eye/40-satellites.webp"><img src="../media/gallery/holly-eye/40-satellites.webp" alt="Спутники в Holly Eye"></a><br><sub>Holly Eye — 830 спутников по данным CelesTrak</sub></td>
<td width="33%"><a href="../media/gallery/holly-eye/03-riga-3d-old-town.webp"><img src="../media/gallery/holly-eye/03-riga-3d-old-town.webp" alt="Рига в 3D в Holly Eye"></a><br><sub>Holly Eye — Рига в 3D</sub></td>
<td width="33%"><a href="../media/gallery/holly-eye/21-live-flights.webp"><img src="../media/gallery/holly-eye/21-live-flights.webp" alt="Рейсы в Holly Eye"></a><br><sub>Holly Eye — рейсы в реальном времени</sub></td>
</tr>
<tr>
<td width="33%"><a href="../media/gallery/holly-eye/24-ais-vessels-channel.webp"><img src="../media/gallery/holly-eye/24-ais-vessels-channel.webp" alt="Суда AIS в Holly Eye"></a><br><sub>Holly Eye — суда по данным AIS</sub></td>
<td width="33%"><a href="../media/gallery/holly-eye/53-active-fires-osm-close.webp"><img src="../media/gallery/holly-eye/53-active-fires-osm-close.webp" alt="Пожары NASA FIRMS в Holly Eye"></a><br><sub>Holly Eye — активные пожары NASA FIRMS</sub></td>
<td width="33%"><sub><b>Ещё в Holly Eye:</b> 14 слоёв данных мира — рейсы, военные рейсы, спутники, космические миссии, землетрясения, пожары, суда, радио, дата-центры, дамбы и другие; стили NVG / FLIR / CRT / Anime / Noir / Snow; сцены; голосовая панель; переход HollyEarth ↔ Holly Eye. → <a href="gallery/HOLLY_EYE.md">46 кадров в галерее Holly Eye</a></sub></td>
</tr>
</table>

Пока не каждая глава Story привязана к конкретным утверждениям. → [Story](gallery/HOLLY_AI.md#story) · [Галерея Holly Eye](gallery/HOLLY_EYE.md) · [Происхождение медиа Holly Eye](../media/HOLLY_EYE_PROVENANCE.md) · [story.md](story.md)

---

## HollyWorlds — эксперименты на Unreal Engine

![HollyWorlds — Unreal Engine](../media/infographics/worlds.svg)

*Концептуальная инфографика, не кадр из Unreal Engine.*

**Не просто наблюдать за миром — перемещаться внутри него.** HollyWorlds — отдельное экспериментальное направление, пока вне веб-платформы v0.1.0. В одном прототипе Unreal Engine есть планетарное географическое окружение, персонаж, вождение и механика стрельбы (по описанию создателей). Второй прототип — **AGLS / Болдерая** — локальная карта, для которой планируются миссии и сюжетные сценарии. Это **отдельные прототипы**: миссии в Болдерае и подключение к HollyEarth Core пока не заявляются как готовые возможности.

---

## Исследования

![HollyEarth — RESEARCH](../media/infographics/research.svg)

*Авторская концептуальная инфографика — визуальная метафора, не скриншот продукта.*

**Большим идеям нужны точные статусы.** Уже реализованы происхождение записей, эпистемические статусы, графовые данные и пространственные представления. HEIO, HEIM и интегральные подходы — это **исследовательские направления**, а не готовые технологии во всей полноте.

Реализовано в v0.1.0: эпистемическая модель (нет безусловного «факта»), происхождение у каждой записи, канонический граф и пространственное представление. HEIO и HEIM — внутренние исследовательские документы, **концептуальная архитектура, а не реализованные функции**. Integral / AQAL, Spiral Dynamics и Integral City — исследовательские влияния; они никогда не используются для оценки людей, партий или районов.

<table>
<tr>
<td width="50%"><a href="../media/concepts/09-heio-concept-architecture.png"><img src="../media/concepts/09-heio-concept-architecture.png" alt="Концептуальная иллюстрация HEIO"></a><br><sub><b>Концептуальная иллюстрация.</b> HEIO — HollyEarth Integral Ontology (v0.1). `RESEARCH`</sub></td>
<td width="50%"><a href="../media/concepts/10-heim-context-system.png"><img src="../media/concepts/10-heim-context-system.png" alt="Концептуальная иллюстрация HEIM"></a><br><sub><b>Концептуальная иллюстрация.</b> HEIM — HollyEarth Integrative Metatheory &amp; Context System (v0.2). `RESEARCH`</sub></td>
</tr>
</table>

→ **[Галерея исследований и концепт-арта](gallery/RESEARCH_CONCEPTS.md)** — в том числе девять концептуальных иллюстраций из истории проекта, каждая помечена как концепт / иллюстрация / не живые данные продукта · [research.md](research.md)

---

## Будущее

![HollyEarth — FUTURE](../media/infographics/future.svg)

*Авторская концептуальная инфографика — визуальная метафора, не скриншот продукта.*

**Открытое сотрудничество. Устойчивое интеллектуальное ядро.** Наша предполагаемая модель — собственное коммерческое ядро и выборочно открываемые инструменты сообщества и самостоятельные проекты. Этот репозиторий пока содержит **только документацию**, а не исходники ядра.

| Есть сегодня | В разработке | Исследование | Будущее |
|---|---|---|---|
| Riga Twin · дела, доказательства, roadmap, Story · данные и паспорта HollySport · Social Intelligence · данные политики и рабочее пространство · мониторинг (вручную) · RU / LV / EN · переход в Holly Eye (сторонняя интеграция) | Общая идентичность между доменами · социальная сфера в основном графе · семантика денег (запланировано → законтрактовано → присуждено → выплачено) · мониторинг по расписанию · проверка человеком · главы Story, привязанные к утверждениям · пилотный хостинг · Event OS, Creator и партнёрства (прототипы) | HEIO · HEIM · Integral / AQAL · Spiral Dynamics (только контекст) · Integral City | Управляемые действия и обжалования · HollyWorlds · экономика MetaSport · публичный хостинг · другие города |

Игровой слой HollySport остаётся `DEMO`, пока не будет построен на реальной механике. → [ROADMAP.md](../ROADMAP.md)

---

## Текущие возможности

![HollyEarth — CAPABILITIES](../media/infographics/capabilities.svg)

*Авторская концептуальная инфографика — визуальная метафора, не скриншот продукта.*

**Мы показываем и возможности, и их зрелость.** Подробная таблица отделяет реально работающие функции от бета-версий, демонстраций, исследований и планов. Концепции не выдаются за готовый продукт.

| Область | Готово к показу | Работает | Бета / прототип | Демо / исследование / будущее |
|---|---|---|---|---|
| Ядро | — | Происхождение · деньги по типам · утверждения со статусом · пространственные слои · RU / LV / EN | Связи между доменами (частично) | Единый граф реальности (`FUTURE`) |
| Город | — | 3D Twin · слои решений, спорта и социальных услуг | Режим исследования · AQAL (`PROTOTYPE`) | Оценки Wellbeing (`DEMO`) |
| Политика | — | Network · Deputies · Parties & Power | Political OS · заседания · решения · бюджет · Evidence Ledger · рабочее пространство | District Impact · Smart City Lenses (`DEMO`) · Integral City (`RESEARCH`) |
| Спорт | Паспорт клуба · паспорт события | Sport City · архив · паспорта · карта · граф | Рейтинги · Event OS · Creator · партнёрства | Игровой слой (`DEMO`) · экономика (`FUTURE`) |
| Социальная сфера | Сцена · досье услуги | Каталог · карта · досье организации · договоры | Деньги · планирование | Потребность, результаты, выплаты (`RESEARCH`) |
| Расследования | Галерея дел · путь доказательства | Рабочее пространство дела · roadmap · анализ · Story | Holly · исследовательские запуски · голос · мониторинг | Процесс проверки человеком (`FUTURE`) |

Полная матрица: **[FEATURE_STATUS.md](FEATURE_STATUS.md)** · [CAPABILITIES.md](../CAPABILITIES.md) · [MODULES.md](../MODULES.md)

## Архитектура и принципы данных

**У каждой записи есть происхождение** · **утверждение ≠ проверенный факт** («verified» в данных никогда не означает проверку человеком, если это не сказано прямо) · **нет записи ≠ нет реальности** · **неизвестно ≠ ноль** · **запланировано ≠ выплачено** · **зарегистрировано ≠ оказано** · **вывод модели ≠ доказательство** · **результаты несовершеннолетних не хранятся** · **демо-данные помечены DEMO**. → [ARCHITECTURE.md](../ARCHITECTURE.md) · [DATA_PRINCIPLES.md](../DATA_PRINCIPLES.md) · [DATA_SOURCES.md](../DATA_SOURCES.md)

Все опубликованные изображения с подписями, статусами и атрибуцией: [media/README.md](../media/README.md).

---

## Авторы / Lab Da Riga

**HollyEarth** создают **Stanislav Petrovsky** и **Irina Petrovskaya**, Рига, Латвия.

© 2026 Lab Da Riga. Все права защищены.

Репозиторий содержит только документацию и медиа. Это **не open source**, исходного кода здесь нет — см. [LICENSE.md](../LICENSE.md) и [NOTICE.md](../NOTICE.md). Карты, данные и компоненты третьих сторон остаются на условиях их владельцев.

## Контакты и новости проекта

**Наш принцип:** показываем созданное, честно отмечаем эксперименты и приглашаем партнёров участвовать в следующем этапе.


- **Следить за проектом** — подпишитесь на этот репозиторий и на [организацию HollyEarth](https://github.com/HollyEarth), чтобы получать релизы и обновления документации.
- **Видео** — видео основателей (зачем мы создаём HollyEarth, что он умеет сегодня, куда идёт дальше) в производстве.
- **Контакты** — официальные каналы связи опубликуют HollyEarth / Lab Da Riga. Вопросы безопасности и персональных данных: см. [SECURITY.md](../SECURITY.md).

История релизов: [CHANGELOG.md](../CHANGELOG.md).
