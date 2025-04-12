package encapsulation;

public class Student {
	private int rollnumber;			// data assigned as private for protection
	private String name;
	private boolean isAttended;
	
	public Student(int rollnumber) {
		this.rollnumber = rollnumber;
	}
	public void setStudentAttendance(boolean flag) {
		if(!isAttended) 
				isAttended = flag;
		isAttended = flag;
		System.out.println("Teacher assigned attendance to the student");
	}
	public boolean getStudentAttendance() {
		System.out.println("Teacher accessed attendance");
		return isAttended;
	}
}
