# clean-code-golang

Inspired from [clean-code-javascript](https://github.com/ryanmcdermott/clean-code-javascript).

## Table of Contents

1. [Introduction](#introduction)
2. [Variables](#variables)



## **Variables**

### Use meaningful and pronounceable variable names

**Bad:**
```go
yyyymmdstr := time.Now().UTC().format("2006/05/21");
```

**Good:**

```javascript
currentDate := time.Now().UTC().format("2006/05/21");
```

**[⬆ back to top](#table-of-contents)**





