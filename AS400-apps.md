# אפליקציות ל-AS/400 (IBM i)

רשימת כלים ואפליקציות נפוצים לעבודה עם AS/400 / iSeries / IBM i, לפי קטגוריה.
מקורות רבים הם אתרי ספקים או פוסטים ישנים. כדאי לבדוק שכל מוצר עדיין נתמך לפני שבוחרים בו.

## 1. אמולטורים למסך 5250 ("מסך ירוק")

| אפליקציה | סוג | הערות |
|---|---|---|
| IBM i Access Client Solutions (ACS) | חינמי מ-IBM | הלקוח הרשמי של IBM. ב-Java, רץ על Windows, Mac ו-Linux. כולל 5250, SQL, ניהול IFS ו-Spool |
| TN5250J | קוד פתוח | אמולטור 5250 ב-Java |
| tn5250 | קוד פתוח | מבוסס טקסט (curses), תומך SSL/TLS |
| Mochasoft TN5250 | מסחרי | פופולרי, יש גם גרסאות ל-iOS ו-Android |
| Turbosoft TTWin / TTerm | מסחרי | Windows, Linux, iPad ודפדפן |

## 2. סביבות פיתוח (IDE)

- **Code for IBM i (תוסף ל-VS Code)**: חינמי וקוד פתוח. עריכת RPG/COBOL/CL, ניהול ספריות ועבודה עם Git.
- **RDi (Rational Developer for i)**: ה-IDE המסחרי של IBM, מבוסס Eclipse.
- **SEU / PDM**: הכלים הקלאסיים במסך הירוק.
- **RPGUnit**: בדיקות יחידה ל-RPG ILE (בדומה ל-JUnit).
- **Liquibase-db2i**: ניהול שינויי סכמה ב-Db2 for i.

## 3. מודרניזציה (מסך ירוק לווב/מובייל, APIs)

- **Profound Logic**: הופך אפליקציות RPG לווב ולמובייל.
- **LANSA (aXes, RAMP, LongRange)**: הופך 5250 לווב בזמן אמת, ומאפשר לבנות אפליקציות מובייל ב-RPG/COBOL/CL.
- **OpenLegacy**: גישה ל-5250 מהדפדפן ו-APIs מאובטחים מעל תוכניות RPG.
- **ARCAD**, **Fresche X-Modernize**, **Programmers.io Green2Glass**: כלי מודרניזציה נוספים.
- **IBM HATS**: אמולטור וממיר של מסכי 5250 ל-HTML.
- **Jitterbit**: אינטגרציה עם AS/400 ו-Db2.

## 4. מערכות ERP שרצות על IBM i

- **Oracle JD Edwards World** (לפי אתרי ביקורות, Oracle מתמקדת כיום ב-EnterpriseOne)
- **Infor LX** (בעבר BPCS)
- **Infor System21**
- **SAP**, ו-**Manhattan Associates** (ש-IBM מציינת כשותפות ERP)

## 5. ניטור

- **Check-as400**: תוסף Nagios לניטור שרת IBM i.

## מקורות

- https://www.ttwin.com/as400-iseries-terminal-emulator
- https://www.Github.com/tn5250j/tn5250j
- https://www.nicklitten.com/what-is-the-best-ibmi-as400-5250-terminal-emulator/
- https://www.nicklitten.com/module/free-or-opensource-5250-emulators/
- https://www.nicklitten.com/?p=25570
- https://www.itjungle.com/2018/05/14/whats-cooking-with-ibm-i-on-github
- https://edge.openlegacy.com/capabilities/as400-ibmi-modernization
- https://lansa.com/blog/ibm-i-modernization/what-is-the-most-robust-ibm-i-green-screen-modernization/
- https://core.profoundlogic.com/solutions/solutions-for-ibm-i-as400-iseries-modernization.html
- https://mcpressonline.com/buyers-guide/software/migration/2314
- https://www.jitterbit.com/wp-content/uploads/Jitterbit-AS400-and-DB2-Modernization-Solution-Sheet.pdf
- https://en.wikipedia.org/wiki/Business_Planning_and_Control_System
- https://slashdot.org/software/erp/for-ibm-i
- https://us.fitgap.com/products/jd-edwards-world
- https://www.ibm.com/support/pages/node/1120197
