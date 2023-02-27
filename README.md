# notes

    
        To create a class inheritance, use the extends keyword.

        A class created with a class inheritance inherits all the methods from another class:

        It maintains an IS-A relationship.
        The extends keyword is used in class expressions or class declarations.
        Using extends keyword, we can acquire all the properties and behavior of the inbuilt object as well as custom classes.
        We can also use a prototype-based approach to achieve inheritance.


        Syntax

                //Super Class   
                class One    
                {    
                 code ;

                }
                return;   
                }    
                //Child Class   
                class Two extends : One   
                {    
                 code; 
                }   
                return;
                }  

                
                Click on the above button to call the welcome method inherited by person1 and person2 object

               Use the "extends" keyword to inherit all methods from another class.
               Use the "super" method to call the parent's constructor function.
 

    <script>
    class Car {
      constructor(brand) {
        this.carname = brand;
      }
      present() {
        return 'I have a ' + this.carname;
      }
    }
    
    class Model extends Car {
      constructor(brand, mod) {
        super(brand);
        this.model = mod;
      }
      show() {
        return this.present() + ', it is a ' + this.model;
      }
    }
    
    let myCar = new Model("Ford", "Mustang");
  console.log(  document.getElementById("demo").innerHTML = myCar.show());
    </script>
   
            The super() method refers to the parent class.

            By calling the super() method in the constructor method,
             we call the parent's constructor method and gets access to the parent's properties and methods.

             Inheritance is useful for code reusability: reuse properties and methods of an existing class
              when you create a new class.
