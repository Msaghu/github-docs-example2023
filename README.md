# Github Docs Example2023

## Writing good documentation
### Step 1 - Using codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, paste,share code**. A good __Cloud Engineer__ uses codeblocks whenever possible because it allows others to copy and paste their code to replicate/ research issues.

- A code block in Golang
```
package main

import (
	"fmt"
	"os"
)

func main() {
	// Deliberate Error: Trying to open a non-existent file
	file, err := os.Open("non_existent_file.txt")
	if err != nil {
		fmt.Println("Error:", err)
		return
	}

	defer file.Close()

	// Attempting to read from the file
	data := make([]byte, 100)
	_, err = file.Read(data)
	if err != nil {
		fmt.Println("Error:", err)
	}
}
```

- When you can, try to apply syntax highlighting to code bloacks
```go
package main

import (
	"fmt"
	"os"
)

func main() {
	// Deliberate Error: Trying to open a non-existent file
	file, err := os.Open("non_existent_file.txt")
	if err != nil {
		fmt.Println("Error:", err)
		return
	}

	defer file.Close()

	// Attempting to read from the file
	data := make([]byte, 100)
	_, err = file.Read(data)
	if err != nil {
		fmt.Println("Error:", err)
	}
}
```

- How to add images 1
![discord92023](https://github.com/Msaghu/github-docs-example2023/assets/77676513/29673492-87bf-419d-b159-b7f7ba386d5c)

- How to add images 2
<img width="400px" src="https://github.com/Msaghu/github-docs-example2023/assets/77676513/29673492-87bf-419d-b159-b7f7ba386d5c" />
