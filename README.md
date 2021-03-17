package person.java;

    public class Customer extends PersonJava {
    
    private String address;
    private double budget;
    

    public void setaddress(String addr){
      this.address=addr;
      }
      public String getaddress(){
      return address;
      }
      public void setbudget(double budgett){
      this.budget=budgett;
      }
      public double getbudget(){
      return budget;
      }
}

package person.java;


public class Employee extends PersonJava{
        private int employeeNum;
    private double basicSalary;

    public void setemployeeNum(double empnumber){
      this.employeeNum=(int) empnumber;
      }
      public int getemployeeNum(){
      return employeeNum;
      }
      public void setbasicSalary(double basSalary){
      this.basicSalary=basSalary;
      }
      public double getbasicSalary(){
      return basicSalary;
      }
}
