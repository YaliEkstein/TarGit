# תרגיט – תרגיל גיט

<p style="text-align:center;">
<img title="Git" alt="Git" src="https://avatars.githubusercontent.com/u/18133?s=100"/>
</p>

## רקע
### מה זה גיט?
- [סרטון](https://www.youtube.com/watch?v=2ReR1YJrNOM&ab_channel=ProgrammingwithMosh)
- [ויקיפדיה](https://en.wikipedia.org/wiki/Git)
### איפה ללמוד גיט?
- [Git documentation](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)
- [GitHub Docs](https://docs.github.com/en)
- [W3schools](https://www.w3schools.com/git/exercise.asp)
- [Atlassian](https://www.atlassian.com/git)
- [LearnGitBranching](https://learngitbranching.js.org/)
### מה נעשה בתרגיט?
- נלמד פקודות בסיסיות ב-command line ומה מטרתן במהלך עבודה שוטף.
- נראה Best practices של גיט.
- ניחשף למצבים בהם ניתקל אולי בעתיד ונראה כיצד לפתור אותם.

### מה לא נעשה בתרגיט?
- התרגיט לא מסביר את התיאוריה שמאחורי גיט, אלא בעיקר את הפרקטיקה.
- נשתדל לא להגיד בדיוק איך לעשות כל דבר. תוכלו ללמוד מהקישורים שבסעיף ב', חיפוש בגוגל או להיעזר בקישורים שמסומנים ב-<ins>underline</ins>.

<p style="text-align:center;">
<br>
<img title="Git" alt="Git" src="https://avatars.githubusercontent.com/u/18133?s=100"/>
</p>

## שלב 0 –GitHub, clone & config 
- וודאו שיש לכם.ן [`git`](https://www.google.com/search?q=download+git+for+windows) על המחשב.
- תגדירו את השם והאימייל שלכם ([`global config`](https://www.google.com/search?q=git+global+config))
- פתחו חשבון `GitHub`.
- מלאו את פרטי החשבון [בטופס הבא](https://forms.gle/MHyxJjmCh8MSHHZg8).
- אשרו את ההזמנה שתשלח לכם במייל.
- עשו [`clone`](https://www.google.com/search?q=git+clone) לתיקייה לבחירתכם על המחשב.
- כל הכבוד! עשיתם.ן `clone`, עכשיו תוכלו להריץ את הקובץ `NextLevel.exe` על ידי [`NextLevel.exe/.`](https://www.google.com/search?q=run+exe+file+in+git+bash)
- בעיה שיכולה להיווצר היא שחסר לכם.ן במחשב Cygwin. רק אם חסר לכם.ן [התקינו](https://www.google.com/search?q=cygwin+download) והוסיפו את `C:\cygwin64\bin` ל-[`environment variables`](https://www.google.com/search?q=add+to+environment+variables)

## שלב 1 – status, add & commit
- הריצו את הפקודה [`git status`](https://www.google.com/search?q=git+status)!
- שימו לב לקובץ חדש שנוצר בתיקייה, השם שלו מופיע באדום (**add**om). 
- הוסיפו אותו לפרויקט עם הפקודה [`git add`](https://www.google.com/search?q=git+add) ושם הקובץ.
- התעלמו מהערות של warning על CRLF.
- הריצו את הפקודה `git status`!!
- שימו לב לשינוי בהדפסה, השם שלו מופיע בירוק (yaroC). 
- שמרו את הגרסה ([`commit`](https://www.google.com/search?q=git+commit)) הזו. תנו את ההערה / ההודעה הבאה:
  - `Added new secrets file`.
- הריצו את הפקודה `git status`!!! שימו לב לשינוי בהדפסה.
- הריצו את `NextLevel.exe`.

## שלב 2 – log & diff 
- חזרו על התהליך משלב 1. עם הדגשים הבאים: 
1) הריצו כל הזמן את הפקודה `git status`!!!!
2) דרך טובה לזכור את סדר הפעולות:   אדום ← `git add`,   ירוק ← `git Commit`
3) חשוב לתת הערות אינפורמטיביות. עשו commit עם ההערה:
`Updated secrets file`. 
- הסתכלו על ה`commit`-ים [האחרונים שנעשו](https://www.google.com/search?q=git+view+commits+history), זהו את הID, היוצר.ת והתאריך של ה-`commit`.
- הסתכלו על [השינוי](https://www.google.com/search?q=git+view+commit+difference) בין ה-`commit` הראשון שעשיתם.ן למצב הנוכחי.
- הריצו את `NextLevel.exe`.

## שלב 3 – pull & push 
- במידה וקוד ה-[`remote`](https://www.google.com/search?q=what+is+remote+in+git) (הקוד המשותף לכולם) השתנה, תצטרכו לעדכן את הקוד הלוקלי (שנמצא רק על המחשב שלכם.ן). עשו זאת על ידי [`git pull`](https://www.google.com/search?q=git+pull).
- נסו לעדכן את קוד ה-`remote` על ידי [`git push`](https://www.google.com/search?q=git+push). האם הצלחתם.ן?
- אם לא הצלחתם.ן סימן שהתרגיל עובד! ננסה לפתור את הבעיה בשלב הבא.

## שלב 4  – branch 
- בדקו באיזה [`branch`](https://www.google.com/search?q=git+branch) (ענף) אתם.ן.
- [צרו](https://www.google.com/search?q=git+create+branch) `branch` חדש, תנו לו שם כלשהו.
- עדכנו את הקוד הlocal ע"י הפקודה `git pull origin` ואז השם של ה-`branch`.
- דחפו את הקוד ה-`local` ל-`remote` באופן דומה.
- [עברו](https://www.google.com/search?q=git+move+to+branch) ל-`branch` לאחר שיצרתם ועדכנתם אותו.
- הריצו את `NextLevel.exe`.

## שלב 5 – ignore
- שימו לב לקובץ חדש שנוצר בתיקייה. האם אתם רואים אותו בהדפסה של `git status`?
- נסו להבין מדוע זה קורה. תנו 3 דרכים לפחות [לפתור את הבעיה](https://www.google.com/search?q=override+gitignore).
- הריצו את `NextLevel.exe`.

## שלב 6 – revert & cherry-pick
- הבינו [הדמיון והשוני](https://www.google.com/search?q=git+difference+between+revert+and+cherry+pick) בין `revert` ל-`cherry-pick`.
- עדכנו את הגרסה של ה-`branch` ב-`remote`.
- שימו לב לשינוי שנעשה לקובץ `NextLevel.exe` ב-`commits` קודמים.
- תזכורת לשני דברים שכדאי תמיד לעשות: `git status` בכל הזדמנות ו-`pull` לפני `push`.
- הריצו את ``NextLevel.exe`` בגרסתו הישנה. במידה ועולה שאלה לגבי Unlink, הקישו `n` ואנטר.

## שלב 7 – merge conflict
- בדקו שאתם על ה-`branch` שיצרתם.ן.
- מישהו עשה שינויים לוקליים ב`main branch`. צפו ב`commit`-ים האחרונים.
- הריצו את הפקודה [`git merge main`](https://www.google.com/search?q=git+merge), שעושה איחוד בין ה`branch`-ים הלוקליים.
- הריצו `git status`!!!! קראו טוב את הפלט. מה השתנה? הסתכלו על הקובץ שהשתנה.
- [פתרו](https://www.google.com/search?q=git+solve+merge+conflict) את הקונפליקט שנוצר, שימו לב להשאיר את הקבצים כפי שאתם רוצים אותם.
- תנו ל`merge commit` את ההערה הבאה: `Merge branch 'main' into ` ואז שם ה`branch`.
- הריצו את `NextLevel.exe`.

## שלב 8 – pull request
- כנסו ל`GitHub` ו[פתחו](https://www.google.com/search?q=github+open+pull+request) `pull request` מה-`branch` שלכם ל`main branch`.
- לאחר שפתחתם, תוכלו לראות איזה בדיקות ([`checks`](https://www.google.com/search?q=github+open+pull+request)) נעשו על ה-`pull request`.
- היכנסו ל`details` של הבדיקה ומצאו את ההודעה שמגלה איך לעבור לשלב הבא.
- לאחר השינויים שעשיתם.ן הריצו את `NextLevel.exe`.

## (מומלץ) שלב 9 – IDEs & GUI
- הריצו את `Reset.exe`.
- חזרו על התהליך של התרגיט, הפעם תעזרו ב-CodeEditor שלכם. ניתן לעשות את הפקודות בקלות ב `PyCharm`, `CLion`, `VSCode` ועוד.
- (לא חובה) ניתן להוריד GUI חיצוני שמציג בצורה נוחה את הפקודות והמצב הנוכחי של הפרויקט.
1)	[GitHub Desktop](https://desktop.github.com/)
2)	[GitKraken](https://www.gitkraken.com/)
3)	[SourceTree](https://www.sourcetreeapp.com/)
- נסו למצוא [קיצורי מקלדת](https://www.google.com/search?q=jetbrains+shortcut+for+vcs) לפקודות.

## כאן נגמר התרגיט
- כעת אתם יכולים לחדד את התיאוריה מאחורי גיט, לנסות ללמוד עוד פקודות שימושיות או להתחיל להשתמש בגיט בפרויקט שלכם.ן.
- Have fun gitting!
