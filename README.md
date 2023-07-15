### Questions

 What is the output of this :
 ```go
package main

func f() (r int) {
	defer func() {
		r++
	}()
	return 0
}

 ```