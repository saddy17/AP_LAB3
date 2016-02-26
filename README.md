package lab3;

public class Note implements java.io.Serializable{
	public String username;
	public String data;
	
	Note(){
		username = "null";
		data = "null";		
	}
	
	Note(String argU, String argD){
		username = argU;
		data = argD;		
	}
}
