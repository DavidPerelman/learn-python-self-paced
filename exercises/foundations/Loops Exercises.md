# מחברת תרגול: לולאות (Loops)

# כל תרגיל יופיע כאן עם התשובה שלך מתחתיו

## תרגיל 1 – לולאת while בסיסית

**הוראה:** יש משתנה שמתחיל ב־1. כל עוד הוא קטן או שווה ל־3, נדפיס אותו ואז נוסיף לו 1.
**תשובה:**
משתנה שווה ל-1
while המשתנה קטן או שווה ל־3:
הדפס את המספר והגדל אותו ב־1

## תרגיל 2 – לולאת for על רשימה

**הוראה:** יש רשימה של מספרים מ־1 עד 3. עבור כל מספר ברשימה, הדפס אותו.
**תשובה:**
רשימה שווה 3
for מספר in רשימה :
הדפס מספר

## תרגיל 3 – לולאת for עם range

**הוראה:** יש טווח מ־1 עד 5. עבור כל מספר בטווח, הדפס אותו.
**תשובה:**
for i in range(0, 5):
print(i + 1)

## תרגיל 4 – לולאה עם תנאי

**הוראה:** יש טווח מ־1 עד 5. עבור כל מספר בטווח, אם המספר זוגי – הדפס 'זוגי', ואם אי-זוגי – הדפס 'אי-זוגי'.
**תשובה:**
for i in range(0, 5):
if i % 2 == 0:
print("זוגי")
else:
print("אי-זוגי")

## תרגיל 5 – תרגיל סיכום

**הוראה:** יש טווח מ־1 עד 6. עבור כל מספר בטווח, אם המספר זוגי – הדפס אותו יחד עם המילה 'זוגי', ואם אי-זוגי – הדפס אותו יחד עם המילה 'אי-זוגי'.
**תשובה:**
for i in range(1, 7):
if i % 2 == 0:
print(i, "זוגי")
else:
print(i, "אי-זוגי")
