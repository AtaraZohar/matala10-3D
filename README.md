<div dir="rtl">

# matala10-3D

במשחק שלנו ישנה סצנה אחת שמתארת עולם שבו ניתן לשוטט, העולם כולל מישור ואיזור ההרי כאשר על המישור בנינו מבנה ע"י שימוש בProgrid 
כדי לבנות את עולם השתמשנו באלמנטים של terrain tools עם מברשות דומות וכדומה.

![](2.png)

בתוך המבנה הקטן שבנינו הופסנו תאורה בעזרת light point בתוך החדר כדי להאיר אותו קצת.

עוד שינוי היה לשנות את הזווית של האור בסצנה כדי שתאיר על כל החדר והוא לא יהיה חשוך.

הוספנו לסצנה גם שחקן שיכול לשוטט בסצנה והמש=צלה תעקוב אחריו. השתמשנו בקודים שראינו בשיעור על מנת שהשחקן יוכל לזוז בלוח וגם בקודים נוספים שנוכל לכוון את זווית המצלמה לפי העכבר.

[CharacterKeyboardMover.cs](Assets/scripts/CharacterKeyboardMover.cs)
[CursorHider.cs](Assets/scripts/CursorHider.cs)
[LookX.cs](Assets/scripts/LookX.cs)
[LookY.cs](Assets/scripts/LookY.cs)

שינוי נוסף שהוספנו היה להחליך את השמיים במשחק לשמיים אחרים עם עננים, עשינו זאת עי שינוי בהגדות האור בתוכנה והורדנו חבילה של skybox על מנת להחליף את השמיים הקיימים.

![](1.png)

 </div>
