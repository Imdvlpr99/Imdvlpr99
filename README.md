```kotlin

class Github {
    var username: String = ""
    var contacts: Map<String, String> = mapOf()
    var aliases: List<String> = listOf()
    var location: String = ""
    var age: String = ""
    var occupation: String = ""
    var operatingSystem: String = ""
    var progLang: List<String> = listOf()

    fun init() {
        username = "Imdvlpr99"
        contacts = mapOf(
            "Instagram" to "yuhuu_saps",
            "LinkedIn" to "Agung Jaya"
        )
        aliases = listOf("imdvlpr", "dev")
        location = "localhost, Indonesia"
        age = "Undefined"
        occupation = "Freelance Developer"
        operatingSystem = "Windows, Linux"
        progLang = listOf("Kotlin", "Java", "Dart", "Javascript", "Typescript")
    }
}

fun main() {
    val github = Github()
    github.init()

    // Accessing the properties
    println("Username: ${github.username}")
    println("Contacts: ${github.contacts}")
    println("Aliases: ${github.aliases}")
    println("Location: ${github.location}")
    println("Age: ${github.age}")
    println("Occupation: ${github.occupation}")
    println("Operating System: ${github.operatingSystem}")
    println("Programming Language: ${github.progLang}")
}

```
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=imdvlpr99&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact" />
</p>
