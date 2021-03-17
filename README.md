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
