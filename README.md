HEAD -- это голова.
Коммит -- это всему голова.
Статусы файлов:

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "git commit -m и текст в кавычках"     --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
``` 




