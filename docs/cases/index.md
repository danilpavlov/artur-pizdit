# Кейсы

Список описанных проектов. Каждый кейс заполнен по [шаблону](../template/index.md).

<div class="case-grid" markdown>

<a class="case-card" href="case-01-example/">
  <div class="case-card__tag">Телеком · Пример</div>
  <h3>01 — Прогноз оттока клиентов</h3>
  <p>Python, LightGBM, Airflow, MLflow. Базовый пример по шаблону.</p>
</a>

<a class="case-card" href="case-02-doxod-ner/">
  <div class="case-card__tag">ДОХОДЪ · NLP</div>
  <h3>02 — NER-маскирование ПДн</h3>
  <p>GliNER, pdfplumber, Tesseract, FastAPI. Recall 0.90–0.95, ускорение ручного процесса.</p>
</a>

<a class="case-card" href="case-03-doxod-resume-ranking/">
  <div class="case-card__tag">ДОХОДЪ · Search</div>
  <h3>03 — Ранжирование резюме с hh.ru</h3>
  <p>BM25, sentence-transformers, Qdrant, Qwen 72B. Автоматизация скрининга откликов.</p>
</a>

<a class="case-card" href="case-04-doxod-segmentation-nba/">
  <div class="case-card__tag">ДОХОДЪ · CRM</div>
  <h3>04 — Сегментация и Next Best Offer</h3>
  <p>HDBSCAN, CatBoost, SHAP, feature store. Персонализация маркетинга и uplift в A/B.</p>
</a>

<a class="case-card" href="case-05-doxod-churn/">
  <div class="case-card__tag">ДОХОДЪ · Мини</div>
  <h3>05 — Прогноз оттока (Churn)</h3>
  <p>CatBoost/LightGBM, SHAP, Airflow. Ранний список под риск для retention.</p>
</a>

<a class="case-card" href="case-06-doxod-spark-feature-store/">
  <div class="case-card__tag">ДОХОДЪ · Data</div>
  <h3>06 — PySpark feature store</h3>
  <p>PySpark, YARN/k8s, Parquet, Airflow. Единая витрина клиентских фичей.</p>
</a>

<a class="case-card" href="case-07-doxod-cashflow-forecast/">
  <div class="case-card__tag">ДОХОДЪ · Time Series</div>
  <h3>07 — Cashflow / AUM forecast</h3>
  <p>Prophet, LightGBM, statsmodels. Планирование ликвидности и операционной нагрузки.</p>
</a>

<a class="case-card" href="case-08-webbee-dynamic-pricing/">
  <div class="case-card__tag">Webbee · E-com</div>
  <h3>08 — Dynamic pricing WB/Ozon</h3>
  <p>LightGBM, Prophet, HDBSCAN, FastAPI. Рост маржи и автоматизация цен.</p>
</a>

<a class="case-card" href="case-09-webbee-card-moderation/">
  <div class="case-card__tag">Webbee · CV</div>
  <h3>09 — Модерация карточек товаров</h3>
  <p>YOLO, CLIP-like, sentence-transformers, Label Studio. Снижение нагрузки модераторов.</p>
</a>

<a class="case-card" href="case-10-webbee-antifraud/">
  <div class="case-card__tag">Webbee · Antifraud</div>
  <h3>10 — Anti-fraud для D2C e-com</h3>
  <p>CatBoost, IsolationForest, Louvain, Redis, SHAP. Realtime в чекауте, снижение чарджбэков.</p>
</a>

</div>

!!! tip "Как добавить новый кейс"
    1. Скопируй директорию `docs/template/` в `docs/cases/case-NN-<short-name>/`.
    2. Добавь подраздел в `nav` внутри `zensical.toml`.
    3. Добавь карточку в сетку выше.
