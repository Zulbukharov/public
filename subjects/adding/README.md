## adding

### Instructions

Create the function `add_curry` that returns a closure.
The purpose is to curry the add method to create more variations.

### Usage

Here is a program to test your function.

```rust
use adding::adding;

fn main() {
    let add10 = add_curry(-10);
    let add20 = add_curry(2066);
    let add30 = add_curry(300000);
    
    println!("{}", add10(5));
    println!("{}", add20(195));
    println!("{}", add30(5696));
}
```

And its output

```console
student@ubuntu:~/[[ROOT]]/test$ cargo run
-5
2261
305696
student@ubuntu:~/[[ROOT]]/test$
```
