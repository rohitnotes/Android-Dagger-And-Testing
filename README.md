# Android Testing Example
* Testing with MVP , Dagger 2 and Retrofit 2
* Required knowledge: MVP  and Retrofit 2.

## Dagger 2 (Dependency Injection)
#### Dependency injection

* Dependency injection is the pattern of the injection of a dependency to a dependent object (a client) that needs it.



* Before you start using dagger, it's important you understand the concepts of dependency injection. Since this is the pattern that allows us to do this kind of testing I find it essential to this example.

* There are 3 types of injection:
  * Constructor injection
  ```
  class Example{
  Dependency dependency
    Example(Dependency dependency){
      this.dependency = dependency;
    }
    
    // ...
  }
  ```
  * Setter/method injection
  ```
  class Example{
  Dependency dependency
    void setDependency(Dependency dependency){
      this.dependency = dependency;
    }
    
    // ...
  }
  ```
  * Property/field injection
    ```
  class Example{
  Dependency dependency
  }
  example.dependency = dependency;
  ```
