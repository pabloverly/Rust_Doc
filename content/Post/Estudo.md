+++
title = "Estudo"
date = 2019-11-14T12:00:00Z
draft = false
+++
# RUST

## PADRAO DE COMENTARIOS 
// = PADRAO C 
/* */ = MULTILINE

## FUNCAO MAIN
FUNÇÃO DE INTERPOINTS = PRIMEIRA FUNCAO A SER CHAMADA
```rust
fn main(){
}
```
## ANOTAÇOES
```rust
/* para permitir variaveis sem uso */
#[allow(unused_variable) ]

```
##   PLACEHOLDER E MACROS
* Para alocação de memoria é necessario ultilizar Placeholder **{}**

* Para identificar as macros usa-se caractere **!**
```rust
fn main (){
    print!("O resultado de 3 + 5 = {}", 3 + 5 );
}
```


## FUNÇÕES
```rust
struct Person {
    name: String, //TIPO DE STRING DINAMICA
    idade: i32
}

// implementa comportamento da struct Person
impl Person{
    fn sayhi(&self) -> String{
        format!("Meu nome é : {} minha idade {}", self.name, self.idade)
    }

}
fn main (){
    //ATRIBUIÇÃO "Pablo" TIPO DE STRINT STATICA 
    let person1 = Person {name: "Pablo".to_string(), idade: 38 };
    let person2 = Person {name: "Bianca".to_string(), idade: 36 };
    
    println!("{}", person1.sayhi());
    println!("{}", person2.sayhi());
}
```




# **TO BE CONTINUE  ...**


## License

MIT
### **SIMBIOSECODE**