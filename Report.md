# รายงานผลการทดลอง

<ณัฐนนท์ ทาไธสง> <รหัสนักศึกษา>

## คำสั่งการแสดงผลผ่าน Logcat

Debug log

Log.debug("This is a debug message")

Error log

Log.error("This is an error message with an additional Exception for output", "AndACustomTag", exception )

Info log

Log.info("This message will not be shown")

Verbose log
Log.v("tag", "This is an info message") 

Warning log

Log.warn("This is a warning message","WithACustomTag")

## SNACKBAR และ TOST

คำสั่งแสดง Snackbar

fab.setOnClickListener { view ->
            Snackbar.make(view, "Replace with your own action", Snackbar.LENGTH_LONG)
                .setAction("Action", null).show()
        }

คำสั่งแสดง Tost
Toast.makeText(this,"button clicked",
                Toast.LENGTH_SHORT).show()
            var i = Intent(this,Main2Activity::class.java)
            startActivity(i)

## Android LiveCycle Activity

จงอธิบาการทำงานของเมธอทต่อไปนี้ ว่าเกิดขึ้นเมื่อใดของโปรแกรม พร้อมแสดงตัวอย่างโค้ดการทำงานของเมธอท (กำหนดให้แสดง log message เมื่อมีการทำงานของเมธอท)

1. onCreate() ->

```kotlin
//Add your code here
```

2. onStart() ->

```kotlin
//Add your code here
```

3. onResume() ->

```kotlin
//Add your code here
```

4. onPause() ->

```kotlin
//Add your code here
```

5. onStop() ->

```kotlin
//Add your code here
```

6. onDestroy() ->

```kotlin
//Add your code here
```

7. onRestart() ->

```kotlin
//Add your code here
```

## Start new Activity

คำสั่งสำหรับเปิด activity ใหม่

```kotlin
//Add your code here
```

คำสั่งสำหรับเปิด activity ใหม่ ผ่านเมนู setting

```kotlin
//Add your code here
```
