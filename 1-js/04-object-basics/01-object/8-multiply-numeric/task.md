importance: 3

---

<<<<<<< HEAD
# ضرب الخصائص الرقمية في 2

أنشئ دالة `multiplyNumeric (obj)` تضرب جميع الخصائص الرقمية لـ `obj` بـ`2`.
=======
# Multiply numeric property values by 2

Create a function `multiplyNumeric(obj)` that multiplies all numeric property values of `obj` by `2`.
>>>>>>> d4b3c135ccf80914f59677803e64ebc832d165e3

على سبيل المثال:

إذا كانت "الرواتب" فارغة ، فيجب أن تكون النتيجة "0".

```js
// before the call
let menu = {
  width: 200,
  height: 300,
  title: "My menu"
};

multiplyNumeric(menu);

// after the call
menu = {
  width: 400,
  height: 600,
  title: "My menu"
};
```

يرجى ملاحظة أن `multiplyNumeric` لا تحتاج إلى إرجاع أي شيء. يجب تعديل الكائن في مكانه.

ملاحظة. استخدم `typeof` للتحقق من وجود رقم هنا. s في 2
