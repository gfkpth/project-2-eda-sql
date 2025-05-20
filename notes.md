# Possible datasets

- nominal person: own dataset
  - notes: done previous linguistic analysis, started creating SQL version, though currently transferring to different data format (CLLD)
  - pro: 
    - I know the dataset (and its shortcomings)
    - want to create a slightly more widely accessible "data story" employing python and data science techniques at some point anyway, using it now might give me a jump start to actually do this
  - cons: 
    - since I want to make this a really good presentation, might be better to do this when we've advanced further?
    - dealing with a different dataset might be useful for exposing me to further diverse data

- linguistic data, e.g. datasets used for NLP-training tasks
  - possible problem: many of these rely on parsing/further processing and/or vectorisation of the actual linguistic input, so often just two columns and all other processes take place later in pipeline, hence maybe not too interesting for EDA and SQL-based analysis?
  - e.g. abusive language detection: https://archive.ics.uci.edu/dataset/543/user+profiling+and+abusive+language+detection+dataset
  - might have interesting room for discussion, although maybe a bit moot for a linguist bc I expect many of the issues for discussion to be extra-linguistic (probably more appealing to non-linguists than something on syntax or morphology though): https://www.kaggle.com/datasets/tayyarhussain/number-of-words-in-different-languages

- language-related statistical data

- statistical data on choice of fields of study in Germany 
  - e.g. data from Statistisches Bundesamt: https://www-genesis.destatis.de/datenbank/online/statistics
  - by state: https://www-genesis.destatis.de/datenbank/online/statistic/21311/table/21311-0006
  - https://www-genesis.destatis.de/datenbank/online/url/50bfb8cb
  - additional extensions: statistics on employment in academia, cf. https://www-genesis.destatis.de/datenbank/online/statistic/21341/details/filter/JTdCJTIyYXJlYUNvZGUlMjIlM0ElMjIlMjIlMkMlMjJjYXRlZ29yeUNvZGUlMjIlM0ElMjIlMjIlMkMlMjJjb2RlJTIyJTNBJTIyMjEzKiUyMiUyQyUyMmNvbnRlbnQlMjIlM0ElMjIlMjIlMkMlMjJ2YXJpYWJsZUNvZGUlMjIlM0ElMjIlMjIlMkMlMjJzb3J0JTIyJTNBJTIyQ29kZUFzYyUyMiUyQyUyMmlzQ29kZVNob3duJTIyJTNBdHJ1ZSUyQyUyMmlzQ2F0ZWdvcnlTaG93biUyMiUzQXRydWUlMkMlMjJpc1ZhcmlhYmxlQ29kZVNob3duJTIyJTNBZmFsc2UlN0Q=
    - Personal an Hochschulen: Deutschland, Jahre, Personalgruppen nach Beschäftigungsverhältnis, Geschlecht
      https://www-genesis.destatis.de/datenbank/online/statistic/21341/table/21341-0001
    - Hauptberufliches wissenschaftliches und künstlerisches Personal an Hochschulen: Deutschland, Jahre, Lehr- und Forschungsbereiche nach Fächergruppen, Geschlecht
      https://www-genesis.destatis.de/datenbank/online/statistic/21341/table/21341-0002
    - Professoren: Deutschland, Jahre, Fächergruppen, Geschlecht
      https://www-genesis.destatis.de/datenbank/online/statistic/21341/table/21341-0003
    - Personal für Forschung und Entwicklung (Vollzeitäquivalente): Deutschland, Jahre, Personalkategorie, Altersgruppen, Dauer des Dienst- oder Arbeitsverhältnisses
      https://www-genesis.destatis.de/datenbank/online/statistic/21811/table/21811-0008/search/s/YWx0ZXJzdmVydGVpbHVuZw==

- employment-related data with linguistics degrees
  - a colleague did this for linguistics graduates at a US university
  - not sure if anything like this available in Germany (or Europe more widely)
  - problem: getting relevant data (they might not exist due to limited tracking and/or accessibility of related data from universities, also: data protection)
