## Nate Ebel - @n8ebel
### Hey devs 👋

I enjoy building great software and helping others do the same.

[![Email n8ebel](https://img.shields.io/badge/Email-n8ebel@goobar.io-red?style=for-the-badge)](mailto:n8ebel@goobar.io)
<br>
[![Website n8ebel](https://img.shields.io/badge/Website-@Goobar.IO-yellow?style=for-the-badge)](https://goobar.io/)
[![YouTube n8ebel](https://img.shields.io/badge/YouTube-@Goobar.IO-red?style=for-the-badge)](https://www.youtube.com/c/goobario?sub_confirmation=1)
[![Twitter n8ebel](https://img.shields.io/badge/Twitter-@n8ebel-9cf?style=for-the-badge)](https://twitter.com/n8ebel)
[![LinkedIn n8ebel](https://img.shields.io/badge/LinkedIn-@n8ebel-blue?style=for-the-badge)](https://www.linkedin.com/in/n8ebel/)


```kotlin
object Nate {
 val name = "Nate Ebel"
 val acknowledgements = "Google Developer Expert"
 
 val primarySkillset = "Android"
 val languages = listOf("Kotlin", "Java", "Python")

 val website = "https://goobar.io/"
 val youtube = "http://youtube.com/c/goobario"
 val contact = "@n8ebel".apply {
   twitter = this
   linkedin = this
   email = "$this@goobar.io"
 }
 
 val publishedBooks = listOf("Mastering Kotlin")
 val publishedCourses 
     = listOf(
         "Getting Started with Android Development", 
         "AD340 - Intro to Android Development",
         "Intro to Kotlin"
         )

}
```
