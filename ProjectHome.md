# [Go MySQL Driver moved to GitHub](https://github.com/go-sql-driver/mysql)! #


---


## Upgrade ##
### 1. Install new package hosted at GitHub ###
Make sure [Git is installed](http://git-scm.com/downloads) on your machine and in your system's `PATH`.
Then simple run in your system's shell:
```
$ go get github.com/go-sql-driver/mysql
```

### 2. Update your code ###
You just need to update your `import`s. Currently you should have something like this in your code:
```
import (
	_ "code.google.com/p/go-mysql-driver/mysql"
)
```

Replace `code.google.com/p/go-mysql-driver/mysql` with `github.com/go-sql-driver/mysql` so that it looks like this:
```
import (
	_ "github.com/go-sql-driver/mysql"
)
```

That's it!

Please follow the development of [Go-MySQL-Driver](https://github.com/go-sql-driver/mysql) at https://github.com/go-sql-driver/mysql.

**Contributions are welcome!**