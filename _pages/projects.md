---
layout: collection
title: "Projects"
collection: projects
permalink: /projects/
entries_layout: grid
classes: wide
---

---

Here are some of my featured projects:

{% include feature_row id="project_features" %}

---

## C++ Projects {#cpp-projects}

### College Assignments in C++

One of my projects involved implementing a small playlist in C++. Below is a link to the repository containing this work, including a Linked List implementation.

- [View C++ Repository on GitHub](https://github.com/javireqs/cpp-projects)

**Code Snippet:**

```cpp
#include "LinkedList.h"

int main() {
    LinkedList<int> list;
    list.add(1);
    list.add(2);
    list.add(3);
    list.display();
    return 0;
}
```

## Python Projects {#python-projects}

### Python Scripts

This Python project showcases a small program using the Fibonacci formula. You can find the code in the GitHub repository below.

- [View Python Repository on GitHub](https://github.com/javireqs/python-projects)

**Code Snippet:**

```python
def fibonacci(n):
    a, b = 0, 1
    for i in range(n):
        print(a)
        a, b = b, a + b
}
```

## Bash Scripts {#bash-scripts}

## Simple Scripts

This Bash/Unix project demonstrates a quick script for backing up a directory. You can explore the repository by following the link below.

- [View Bash/Unix Repository on Github](https://github.com/javireqs/bash-scripts)

**Code Snippet:**

```bash
#!/bin/bash
# Simple script to back up a directory

backup_dir="/path/to/dir"
dest_dir="/path/to/backup"

cp -r $backup_dir $dest_dir
echo "Backup complete!"
```

## Web Projects {#web-projects}

## Javascript - HTML - CSS

This web project demonstrates a simple webpage. You can explore the repository by following the link below.

- [View Web Projects Repository on Github](https://github.com/javireqs/web-projects)

**Code Snippet:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Web Project</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1>Welcome to My Project</h1>
    <p>This is a simple website built using HTML, CSS, and JavaScript.</p>
</body>
</html>
```