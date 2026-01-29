---
layout: post
title: "Testing Syntax Highlighting"
date: 2026-01-29
---

This is a test post to demonstrate syntax highlighting on the blog.

## Python Example

```python
def fibonacci(n):
    """Generate Fibonacci sequence up to n terms."""
    a, b = 0, 1
    for i in range(n):
        print(a, end=' ')
        a, b = b, a + b
    print()

# Test the function
fibonacci(10)
```

## Bash Example

```bash
#!/bin/bash

# Update system packages
sudo xbps-install -Su

# Install Ruby and development tools
sudo xbps-install -S ruby ruby-devel gcc make

echo "Installation complete!"
```

## C Example

```c
#include <stdio.h>

int main() {
    int n = 10;
    printf("Hello, World!\n");
    printf("The number is: %d\n", n);
    return 0;
}
```

## Inline Code

You can also use inline code like `sudo xbps-install` or `print("hello")` within text.
