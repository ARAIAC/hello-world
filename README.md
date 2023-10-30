Rust Notes:
- _ is skip
- Variables start as imutable, f = mut
- Shorthand syntax, example: x += 2; == x = x + 2;
  - Better example:
// Fill the blanks in the code to make it compile
// fn main() {
    let mut x: i32 = 1;
    x += 2; 
    
    assert_eq!(x, 3);
    println!("Success!");
}
- 
