# git add

> Додає змінені файли до індексу.
> Більше інформації: <https://git-scm.com/docs/git-add>.

- Додає змінені файли до індексу:

`git add {{шлях/до/файлу}}`

- Додає усі файли (контрольовані та неконтрольовані):

`git add {{[-A|--all]}}`

- Додає тільки ті файли, що вже контрольовані:

`git add {{[-u|--update]}}`

- Додає й ті файли, що ігноруються:

`git add {{[-f|--force]}}`

- Інтерактивно індексує частини файлів:

`git add {{[-p|--patch]}}`

- Інтерактивно індексує частини вказаного файлу:

`git add {{[-p|--patch]}} {{шлях/до/файлу}}`

- Інтерактивно індексує файл:

`git add {{[-i|--interactive]}}`
