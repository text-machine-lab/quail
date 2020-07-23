# QuAIL: Question Answering for Artificial Intelligence

This repository contains the main and challenge data for QuAIL reading comprehension dataset. QuAIL contains 15K multi-choice questions in texts 300-350 tokens long 4 domains (news, user stories, fiction, blogs). QuAIL is **balanced and annotated for question types**:
 
 > - **text-based questions** (the information should be found in the text):
>   * reasoning about factual information in the text (e.g. *What did John do?*);
>   * temporal order of events (e.g. *When did X happen - before, after, or during Y?*);
>   * character identity (e.g. *Who ate the cake?*);
> - **world knowledge questions** (rely on some kind of inference about characters and events, based on information in the text and world knowledge):
>   * causality (e.g. *Why did John eat the cake?*);
>   * properties and qualities of characters (e.g. *What kind of food does John probably like?*);
>   * belief states (e.g. *What does John think about Mary?*); 
>   * subsequent state after the narrated events (e.g. *What does John do next?*);
>   * duration of the narrated events (e.g. *How long did it probably take John to eat the cake?*);
> - **unanswerable questions** are questions for which the information is not found in the text, and all answer options are equally likely (e.g. *What is John's brother's name?*)

See the blog post describing the project and updates post-paper-publication: https://text-machine-lab.github.io/blog/2020/quail

Published paper: https://aaai.org/ojs/index.php/AAAI/article/view/6398

Leaderboard: http://text-machine.cs.uml.edu/lab2/projects/quail/

Leaderboard submission instructions: https://worksheets.codalab.org/worksheets/0xcb1727289e2b4688b6534c8253b3bc8e

