# assignmentapril25-29

## string reverse

package myProjects;

public class Recstringrev {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		String n="hello";
		stringrev(n);

	}

	private static String stringrev(String n) {
		if(n.isEmpty()) {
			System.out.print(n);
			return n;
		}
		else {
			System.out.print(n.charAt(n.length()-1));
			return stringrev(n.substring(0,n.length()-1));
		}
	
		
	}

}
