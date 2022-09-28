# Inharitance.java
// Inharitance..................
class Patient{
	String name;
	int wardNumber; 
	public void Display(){
		System.out.println(name);
		System.out.println(wardNumber);
	}
}
public class Inharitance{
	public static void main(String[] args){
		Patient P1=new Patient();
		P1.name="Radha";
		P1.wardNumber=123;
		P1.Display();
		Patient P2=new Patient();
		P2.name="Rajesh";
		P2.wardNumber=132;
		P2.Display();
	}
}
