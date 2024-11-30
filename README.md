# OVERRIDDING
IN THIS CODE WE STUDY HOW TO IMPLEMENT OVERRIDING IN JAVA


package face;
import java.util.Scanner;

class over{
	
	
	void display() {
		System.out.println("what is yoy name");
		
	}
}

class overr extends over{
	void display() {
		System.out.println("my name is ");
		
	}
}

public class Overridding {

	public static void main(String[] args) {
		over O=new over();
		O.display();
		over t=new overr();
		t.display();

	}

}


