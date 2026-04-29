# English Lessons Dashboard

> Головна сторінка бази для уроків англійської з викладачем.

## Швидкі посилання

- [[Learning Goals]]
- [[Homework Tracker]]
- [[Mistake Bank]]
- [[Vocabulary Bank]]
- [[Grammar Notes]]
- [[Pronunciation Notes]]
- [[Teacher Feedback]]
- [[Resources]]

---

## Останні уроки

- [[2026-04-29 Lesson 01]]

> Якщо встановиш плагін **Dataview**, можна використовувати цей блок:

```dataview
TABLE date AS "Date", topic AS "Topic", status AS "Status"
FROM "01_Lessons"
SORT date DESC
LIMIT 10
```

---

## Активні домашні завдання

```dataview
TABLE due AS "Deadline", status AS "Status"
FROM "06_Homework"
WHERE status != "done"
SORT due ASC
```

---

## Мої головні фокуси

- [ ] Говоріння
- [ ] Граматика
- [ ] Вимова
- [ ] Словниковий запас
- [ ] Письмо
- [ ] Аудіювання
