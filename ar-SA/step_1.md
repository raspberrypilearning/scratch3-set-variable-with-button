أضف كائنًا ليكون بمثابة زر.

![](images/add-sprite.png)

**نصيحة:** أي كائن يمكن أن يكون زر ولكن هناك بالفعل بعض زر في Scratch التي يمكنك استخدامها.

![](images/button-sprites.png)

انقر على `متغيرات`{: class = "block3variables"} مجموعة قائمة و ثم **انشاء متغير** زر.

امنح المتغير ``{: class = "block3variables"} اسمًا يسهل التعرف عليه.

![](images/name-variable.png)

ستحتاج إلى إضافة شفرة برمجية إلى الكائن زر لتحديث المتغير ``{: class = "block3variables"}. يمكنك:

+ استخدم زر لتعيين ``{: class = "block3variables"} المتغير ``{: class = "block3variables"} إلى قيمة جديدة.

```blocks3
when this sprite clicked
set [speed v] to (10)
```

+ استخدم الزر لتعيين ``{: class = "block3variables"} المتغير ``{: class = "block3variables"} إلى قيمة جديدة.

```blocks3
when this sprite clicked
change [score v] by (1)
```

+ استخدم زر`اسال`{: فئة = "block3sensing"} سؤال و `لجعل`{: فئة = "block3variables"} قيمة `المتغير`{: فئة = "block3variables"} إلى `الجواب`{: فئة = "block3sensing"}.

```blocks3
when this sprite clicked
ask [What is your name?] and wait 
set [name v] to (answer)
```
