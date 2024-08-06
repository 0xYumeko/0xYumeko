### Hi  everyone 👋
![photo_2024-05-10_16-58-22](https://github.com/0x3f3c/0x3f3c/assets/154844497/125a6162-ab3f-4d54-9a5d-aef631e1ce5b)

```
package main

import (
    "fmt"
    "strconv"
)

func main() {
    hexValue := "0x3F3C"
    
    // Convert the hexadecimal string to an integer
    decimalValue, err := strconv.ParseInt(hexValue, 0, 64)
    if err != nil {
        fmt.Println("Error converting hexadecimal to decimal:", err)
        return
    }
    
    // Print the decimal value
    fmt.Printf("The decimal value of %s is %d\n", hexValue, decimalValue)
}

```
<!--
**0x3f3c/0x3f3c** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
