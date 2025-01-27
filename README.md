# Run-time
package javaapplication12;
class animal{
    void sound(){
        System.out.println("animal makes a sound");
    }
}
class dog extends animal{
    @Override
    void sound(){
        System.out.println("dog barks");
    }
}
class cat extends animal{
    @Override
    void sound(){
        System.out.println("cat meows");
    }
}  
   
public class JavaApplication1
    public static void main(String[] args) {
        animal animal;
        animal=new dog();
        animal.sound();
        animal=new cat();
        animal.sound();
    }
    
    }
  Output:
dog barks
cat meows
