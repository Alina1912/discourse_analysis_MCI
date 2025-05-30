# Comparison Of Discourse Parameters In Older People With And Without Mild Cognitive Impairment (MCI)
Данный репозиторий содержит код и материалы дипломной работы на тему "<b> Сравнение характеристик дискурса у пожилых в норме и с синдромом мягкого когнитивного снижения (МКС) </b>". 

<i> Синдром мягкого когнитивного снижения (МКС) является промежуточной стадией между нормальным старением и деменцией.</i>

Основной целью данной работы было выявление лингвистических маркеров, которые могли бы служить для диагностики когнитивного снижения на ранних стадиях нейродегенеративных изменений, а также для классификации пациентов на две группы: пациентов с синдромом МКС и пожилых людей при здоровом когнитивном старении.

---
(Eng) This repository contains the code and resources for the study titled "Comparison of Discourse Parameters in Older People with and without Mild Cognitive Impairment". The research focuses on identifying linguistic and emotional markers in spontaneous speech that differentiate between cognitively healthy older adults and those with Mild Cognitive Impairment (MCI). The study employs natural language processing (NLP) techniques, statistical analysis, and sentiment analysis to explore these differences.

## 🔍 Основные возможности
- Анализ лексико-семантических характеристик речи
- Оценка эмоциональной тональности дискурса (на основе словаря РуСентиЛекс)
- Выявление речевых маркеров когнитивных нарушений
- Статистическое сравнение групп (группа с синдромом МКС VS группа при нормальном когнитивном старении)
  
# Анализ дискурса при мягких когнитивных нарушениях (МКС)

Данный репозиторий содержит код и материалы для исследования **"Сравнение характеристик дискурса у пожилых людей в норме и с синдромом легкого когнитивного снижения"**. В работе изучаются лингвистические и эмоциональные маркеры спонтанной речи, позволяющие дифференцировать когнитивно здоровых пожилых людей и пациентов с легкими когнитивными нарушениями (ЛКН). В исследовании применяются методы обработки естественного языка (NLP), статистического анализа и анализа тональности.

## Структура репозитория

Репозиторий включает четыре блокнота Jupyter (файлы `.ipynb`), каждый из которых посвящен отдельному аспекту анализа:

1. **`statistical_analysis.ipynb`**  
   - Вычисляет лексико-семантические характеристики речи (например, количество слов, соотношение местоимений к существительным, глаголов к существительным).  
   - Проводит статистическое сравнение между группой с синдромом МКС и группой пожилых людей при здоровом когнитивном старении для выявления значимых различий.

2. **`sentiment_analysis.ipynb`**  
   - Анализирует эмоциональную тональность дискурса с использованием словаря РуСентиЛекс.  
   - Классифицирует дискурсы на позитивные, нейтральные и негативные на основе лексического содержания.

3. **`memory_complaints_1.ipynb`**  
   - Выявляет и подсчитывает фразы, указывающие на жалобы на память (например, "забыл", "не могу вспомнить") и хезитации (например, "ну", "это") с помощью регулярных выражений.  
   - Сравнивает частоту этих маркеров между группами.

4. **`correlations.ipynb`**  
   - Исследует взаимосвязи между:  
     - Показателями когнитивных функций (MoCA) и демографическими факторами (возраст, образование).  
     - Эмоциональным состоянием (HADS-A для тревоги, HADS-D для депрессии) и характеристиками дискурса (тональность, жалобы на память, хезитации).  
     - Стрессогенными событиями и эмоциональными/когнитивными показателями.

## Ключевые результаты

- **Лексико-семантические различия**: Группа с синдромом продемонстрировала меньшую длину дискурса, сниженное лексическое разнообразие и более высокое соотношение местоимений к существительным и глаголов к существительным по сравнению с контрольной группой.  
- **Эмоциональная тональность**: Хотя большинство дискурсов были позитивно окрашены (из-за специфики задания на порождение устной речи (описание памятных и ярких воспоминаний), депрессивные симптомы ( по шкале HADS-D) коррелировали с увеличением доли нейтральных/негативных дискурсов в группе с синдромом МКС.  
- **Жалобы на память**: Значимых различий между группами не было выявлено, но качественный анализ показал особенности организации автобиографического повествования у пожилых людей.  
- **Когнитивный резерв**: Уровень образования и возраст участников положительно коррелировали с баллами по шкале MoCA в группе с синдромом МКС, что подтверждает теорию когнитивного резерва.  

## Методология

- **Данные**: Образцы спонтанной речи 200 участников (100 с диагностированным синдромом МКС из Клиники Памяти (Москва, Россия), 100 из контрольной группы при здоровом когнитивном старении), описывающих памятные события из жизни (любимый праздник/ самый лучший подарок, который получали/ памятная поездка).  
- **Инструменты**: Библиотеки Python для NLP (например, `pymorphy2` для лемматизации), статистических тестов (например, U-критерий Манна-Уитни, корреляция Спирмена) и анализа тональности (словарь РуСентиЛекс).  
- **Метрики**:  
  - Лексические (частотность слов, соотношение частей речи (имена существительные, глаголы, личные местоимения), длина дискурса).  
  - Прагматические (хезитации, фразы, маркирующие нарушения в работе памяти).  
  - Эмоциональные (оценка тональности дискурсов).  

## Использование

1. Клонируйте репозиторий:  
   ```bash
   git clone https://github.com/Alina1912/discourse_analysis_MCI.git
## 🛠️ Установка и запуск

1. Клонировать репозиторий:
```bash
git clone https://github.com/Alina1912/discourse_analysis_MCI.git
cd discourse_analysis_MCI
```

Запустить Jupyter Notebook:

```bash
jupyter notebook
```

## 📊 Основные результаты

| Параметр                      | Группа ЛКН (n=100) | Контрольная группа (n=100) | p-value  |
|-------------------------------|--------------------|---------------------------|----------|
| Длина дискурса (слова)        | 102.4 ± 56.9       | 128.0 ± 75.7              | <0.01**  |
| Соотношение местоимений/существительных | 0.45 ± 0.31    | 0.39 ± 0.24               | 0.037*   |
| Соотношение глаголов/существительных   | 0.87 ± 0.29    | 0.77 ± 0.26               | 0.028*   |

<small>** p < 0.01, * p < 0.05 — уровень статистической значимости</small>

## Библиография
## Основные публикации по теме, на которые мы ссылались в исследовании:
1. Ahmed, S., Arnold, R., Thompson, S. A., Graham, K. S., & Hodges, J. R. (2008). Naming of objects, faces and buildings in mild cognitive impairment. Cortex, 44(6), 746–752. https://doi.org/10.1016/j.cortex.2007.02.002

2. Bilodeau‐Mercure, M., & Tremblay, P. (2016). Age Differences in Sequential Speech Production: Articulatory and Physiological Factors. Journal of the American Geriatrics Society, 64(11). https://doi.org/10.1111/jgs.14491

3.Boschi, V., Catricalà, E., Consonni, M., Chesi, C., Moro, A., & Cappa, S. F. (2017). Connected Speech in Neurodegenerative Language Disorders: A Review. Frontiers in Psychology, 8. https://doi.org/10.3389/fpsyg.2017.00269

4. Gosztolya, G., Vincze, V., Tóth, L., Pákáski, M., Kálmán, J., & Hoffmann, I. (2019). Identifying Mild Cognitive Impairment and mild Alzheimer’s disease based on spontaneous speech using ASR and linguistic features. Computer Speech & Language, 53, 181–197. https://doi.org/10.1016/j.csl.2018.07.007

5. Kim, H., Hillis, A. E., & Themistocleous, C. (2024). Machine Learning Classification of Patients with Amnestic Mild Cognitive Impairment and Non-Amnestic Mild Cognitive Impairment from Written Picture Description Tasks. Brain Sciences, 14(7), 652. https://doi.org/10.3390/brainsci14070652

6. López-de-Ipiña, K., Alonso, J. B., Solé-Casals, J., Barroso, N., Henriquez, P., Faundez-Zanuy, M., Travieso, C. M., Ecay-Torres, M., Martínez-Lage, P., & Eguiraun, H. (2015). On Automatic Diagnosis of Alzheimer’s Disease Based on Spontaneous Speech Analysis and Emotional Temperature. Cognitive Computation, 7(1), 44–55. https://doi.org/10.1007/s12559-013-9229-9

7. Lyashevskaya, O. N., & Sharov, S. A. (2009). Chastotny`j slovar` sovremennogo russkogo yazyka na materialax Nacional`nogo korpusa russkogo yazyka. Izdatel`skij centr "Azbukovnik".

8. Petersen, R. C., Smith, G. E., Waring, S. C., Ivnik, R. J., Tangalos, E. G., & Kokmen, E. (1999). Mild Cognitive Impairment: Clinical Characterization and Outcome. Archives of Neurology, 56(3), 303. https://doi.org/10.1001/archneur.56.3.303

9. Richard, A. B., Lelandais, M., Reilly, K. T., & Jacquin-Courtois, S. (2024). Linguistic Markers of Subtle Cognitive Impairment in Connected Speech: A Systematic Review. Journal of Speech, Language, and Hearing Research, 67(12), 4714–4733. https://doi.org/10.1044/2024_JSLHR-24-00274

10. Szatloczki, G., Hoffmann, I., Vincze, V., Kalman, J., & Pakaski, M. (2015). Speaking in Alzheimer’s Disease, is That an Early Sign? Importance of Changes in Language Abilities in Alzheimer’s Disease. Frontiers in Aging Neuroscience, 7. https://doi.org/10.3389/fnagi.2015.00195

11.Venneri et al. 2016 — A. Venneri, M. Mitolo, M. De Marco. Paradigm shift: semantic memory decline as a biomarker of preclinical Alzheimer’s disease // Biomarkers in Medicine. 2016. Vol. 10. No. 1. P. 5–8.

12. Vincze, V., Gosztolya, G., Tóth, L., Hoffmann, I., Szatlóczki, G., Bánréti, Z., Pákáski, M., & Kálmán, J. (2016). Detecting Mild Cognitive Impairment by Exploiting Linguistic Information from Transcripts. Proceedings of the 54th Annual Meeting of the Association for Computational Linguistics (Volume 2: Short Papers), 181–187. https://doi.org/10.18653/v1/P16-2030

13. Vincze, V., Szabó, M. K., Hoffmann, I., Tóth, L., Pákáski, M., Kálmán, J., & Gosztolya, G. (2022). Linguistic Parameters of Spontaneous Speech for Identifying Mild Cognitive Impairment and Alzheimer Disease. Computational Linguistics, 48(1), 119–153. https://doi.org/10.1162/coli_a_00428




## 📧 Контакты
По вопросам или сотрудничеству пишите на [shishcova.alina@gmail.com].

Репозиторий: https://github.com/Alina1912/discourse_analysis_MCI

## Citation
If you use this code or findings in your research, please cite the original work:
<i>Shishkova, A. (2025). Comparison of Discourse Parameters in Older People with and without Mild Cognitive Impairment. National Research University Higher School of Economics.</i>

При использовании кода или результатов исследования просьба ссылаться на оригинальную работу:
<i>Шишкова А. (2025). Сравнение характеристик дискурса у пожилых людей в норме и с синдромом легкого когнитивного снижения. Национальный исследовательский университет "Высшая школа экономики".</i>

