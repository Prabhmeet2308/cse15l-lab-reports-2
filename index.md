import static org.junit.Assert.*;
import org.junit.*;

public class SkillDemoTest{
  @Test
  public void multiplication(){
    assertEquals(4,SkillDemo.multiply(4*2));
  }
}

ssh cs15lsp22aui@ieng6.ucsd.edu

git clone link
ls

cd skill-demo

javac -cp .:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar SkillDemoTest.java
java -cp .:lib/junit-4.13.2.jar:lib/hamcrest-core-1.3.jar org.junit.runner.JUnitCore SkillDemoTest

git pull
