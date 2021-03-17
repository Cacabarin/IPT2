package person.java;

public class Manager extends Employee {
        private int allowance;

    public void setallowance(int allowances){
    this.allowance=allowances;    
    }
    public int getallowace(){
    return allowance;
    }
}

package person.java;

public class Secretary extends Employee {
    
    
}
package person.java;

public class SalesPerson extends Employee {
        private double commission;

    public void setcommission(double commissionn){
    this.commission=commissionn;
    }
    public double getcommission(){
    return commission;
    }

    public void takeOrder(){
        System.out.println("Can i take your Orders Ma'am/Sir?");
    }
}
