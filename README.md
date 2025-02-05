# AutomationFirst

adding two number

10+20=30


public class Employee extends Person
{
    private String name;

    public Employee(String name)
    {
      this.name = name;
    }
    public String getName()
    {
       return this.name;
    }
    public static void main (String args[])
    {
        Employee employee = new Employee("John Wilson");

        System.out.println("Employee's Name "+ employee.getName());
        
