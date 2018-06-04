# encapsulation-example
class Encapsulation{
    private int id;
    private String empName;
    private int empAge;

    //Getter and Setter methods
    public int getEmpid(){
        return id;
    }

    public String getEmpName(){
        return empName;
    }

    public int getEmpAge(){
        return empAge;
    }

    public void setEmpAge(int newValue){
        empAge = newValue;
    }

    public void setEmpName(String newValue){
        empName = newValue;
    }

    public void setEmpid(int newValue){
        id = newValue;
    }
}
public class EncapsTest{
    public static void main(String args[]){
         Encapsulation emp = new Encapsulation();
         emp.setEmpName("balu");
         emp.setEmpAge(24);
         emp.setEmpid(12540);
         System.out.println("Employee Name: " + emp.getEmpName());
         System.out.println("Employee id: " + emp.getEmpid());
         System.out.println("Employee Age: " + emp.getEmpAge());
    } 
}
