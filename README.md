```
class Github {
    var username: String = ""
    var contacts: Map<String, String> = mapOf()
    var aliases: List<String> = listOf()
    var location: String = ""
    var age: String = ""
    var occupation: String = ""
    var operatingSystem: String = ""

    fun init() {
        username = "Imdvlpr99"
        contacts = mapOf(
            "Instagram" to "yuhu_saps",
            "LinkedIn" to "Agung Jaya"
        )
        aliases = listOf("imdvlpr", "dev")
        location = "localhost, Indonesia"
        age = "Undefined"
        occupation = "Freelance Developer"
        operatingSystem = "Windows, Linux"
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
}

```
