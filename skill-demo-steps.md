public static int multiply(int n, int m){
  return n*m
}


import static org.junit.Assert.*;
import org.junit.*;

public class SkillDemoTest{
  @Test
  public void multiply(){
    assertEquals(4,SkillDemo.multiply(4*2));
  }
}
download files add in lib folder 
commit
push


ssh cs15lsp22aui@ieng6.ucsd.edu

git clone https://github.com/Prabhmeet2308/skill-demo.git
ls

cd skill-demo

javac -cp .:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar SkillDemoTest.java
java -cp .:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar org.junit.runner.JUnitCore SkillDemoTest

git pull
