# Excercise-11
getters/setters


import java.util.Scanner;

/*
*Jonathan Saldivar
*ITSE 1302-011
*Exercise 11
*Setting attributes for the AddressBook to pull from
*/

public class Person {

  public static void main (String [] strArgs) {
  
    private String strFirstName = "";
    private String strLastName = "";
    private String strMiddleName = "";
    private char chrGender = ' ';
    private int intBirthDay = 21;
    private int intBirthMonth = 9;
    private int intBirthYear = 1993;
    private int intHeighIn = 67;
    private int intWeightLBS = 160;
    
    
    Scanner onjInput = new Scanner(System.in);
    
    public void setFirstName(String pstrFirstName) {
        strFirstName = pstrFirstName;
}
    public String getFirstName() {
    System.out.println("Type in your First Name: ");
    strFirstName = objInput.next().toUpperCase();
    return strFirstName;
    
    }
    
       public void setLastName(String pstrLastName) {
          strLastName = pstrLastName;
          
       }
       public String getLastName() {
       System.out.println("Type in your Last Name: ");
       strLastName = objInput.next().toUpperCase();
       return strLastName;
       
       }
       
          public void setMiddleName(String pstrMiddleName) {
          strMiddleName = pstrMiddleName;
          }
          public String getMiddleName() {
          System.out.println("Type in your Middle Name: ");
          strMiddleName = objInput.next().toUpperCase();
          return strMiddleName;
          }
           
             public void setBirthDay(int pintBirthDay) {
               intBirthDay= pintBirthDay;
               }
               public int getBirthDay() {
               System.out.println("Type in your birth day: ");
               intBirthDay = objInput.next().toUpperCase();
               return intBirthDay;
               }
               
                 public void setBirthMonth(int pintBirthMonth) {
                   intBirthMonth = pintBirthMonth;
                   }
                   public int getBirthMonth() {
                   System.out.println("Type in your birth month: ");
                   intBirthMonth = objInput.next().toUpperCase();
                   return intBirthMonth;
                   }
                   
                      public void setBirthYear(int pintBirthYear) {
                       intBirthYear = pintBirthYear;
                       }
                       public int getBirthYear() {
                       System.out.println("Type in your birth year: ");
                       intBirthYear = objInput.next().toUpperCase();
                       return intBirthYear;
                       }
                       
                          public void setGender(String pstrGender) {
                           strGender = pstrGender;
                           }
                           public String getGender() {
                           System.out.println("Type in your Gender: ");
                           strGender = objInput.next().toUpperCase();
                           return strGender;
                           }
                           
                              public void setHeightIn(int pintHeightIn) {
                               intHeightIn = pintHeightIn;
                               }
                               public int getHeightIn() {
                               System.out.println("Type in your height: ");
                               intHeightIn = objInput.next().toUpperCase();
                               return intHeightIn;
                               }
                               
                                   public void setWeightLBS(String pstrFirstName) {
                                   strFirstName = pstrFirstName;
                                   }
                                   public int getWeightLBS() {
                                   System.out.println("Type in your First Name: ");
                                   strFirstName = objInput.next().toUpperCase();
                                   return strFirstName;
                                   }
                                   
                                       public void setFirstName(String pstrFirstName) {        strFirstName = pstrFirstName;}    public String getFirstName() {    System.out.println("Type in your First Name: ");    strFirstName = objInput.next().toUpperCase();    return strFirstName;        }
                                       
                                           public void setFirstName(String pstrFirstName) {        strFirstName = pstrFirstName;}    public String getFirstName() {    System.out.println("Type in your First Name: ");    strFirstName = objInput.next().toUpperCase();    return strFirstName;        }
    
    Person objPerson = new Person();
    System.out.println(objPerson.getStats());//Shows the stats from Person class to show here
  
  }
  }
