import java.util.*;

import javax.lang.model.util.ElementScanner14;

import java.time.*;
public class Vechicle_rental {
    static Scanner sc=new Scanner(System.in);
    static int h,id=1000,jj,usid=100,poo=0;
    static String h1="",kas="";
    static ArrayList<String>l=new ArrayList<>();
    static ArrayList<String>l1=new ArrayList<>();
    
    static ArrayList<String>l2=new ArrayList<>();
    static ArrayList<String>l3=new ArrayList<>();
    static ArrayList<String>l4=new ArrayList<>();
    static ArrayList<Integer>l8=new ArrayList<>();
    static ArrayList<String>l11=new ArrayList<>();
   
    static ArrayList<String>b=new ArrayList<>();
    static ArrayList<String>b1=new ArrayList<>();
   
    static ArrayList<String>l5=new ArrayList<>();
   static ArrayList<String>l6=new ArrayList<>();
    static ArrayList<Integer>l7=new ArrayList<>();
    
    static ArrayList<String>l9=new ArrayList<>();
    static ArrayList<String>l10=new ArrayList<>();
    static ArrayList<String>l12=new ArrayList<>();
    


    
     public static void main(String[] args)throws Exception {
        l2.add("TN 33 BV 8397");
        l3.add("CAR");
        l4.add("55");
        l8.add(1000);
        l9.add("30000");
        l11.add("1500");
        l7.add(100);
         welcome();
        
    }
    public static void welcome()
    {
        System.out.print("\033[H\033[2J");
        System.out.flush();
        System.out.println("\t\tWELCOME TO RENTAL SHOP");
        System.out.println();
        System.out.println("1.Ad");
        System.out.println("2.BORROWER");
        System.out.println("3.EXIT");
        System.out.println();
        System.out.println("ENTER THE CHOICE");
        h=sc.nextInt();
        home();
    }
    public static void home()
    {
        if(h<1||h>3)
        welcome();
        else
        switch(h)
        {
            case 1: Ad();
            case 2: user();
            case 3: welcome();

        }
    }
    public static void Ad()
    {
        System.out.print("\033[H\033[2J");
        System.out.flush();
        System.out.println("\t\tWELCOME Ad");
        System.out.println();
        System.out.println("1.ENTER YOUR NAME");
        h1=sc.next();
        System.out.println();
        System.out.println("ENTER YOUR ID");
        String h2=sc.next();
        if(h1.contains("JAWA")&&h2.contains("10")||l.contains(h1)&&l1.contains(h2))
        {
            Ad1();
        }
        else{
            System.out.println();
            System.out.println("\t\tYOUR  DETAILS ARE NOT REGISTERED!!!");
            System.out.println();
            sc.nextLine();
            System.out.println();
            System.out.println("====PRESS ENTER TO CONTINUE====");
	        sc.nextLine();
	        String s=sc.nextLine();
	        if(s.equals(""))
            welcome();
        }
    }
    public static void Ad1()
    {
        System.out.print("\033[H\033[2J");
        System.out.flush();
        System.out.println("\t\t!!!  HELLO "+h1+"  !!!");
        System.out.println();
        System.out.println("1.ADD Ad");
        System.out.println("2.ADD Vechicle_rental");
        System.out.println("3.VIEW Vechicle_rental");
        System.out.println("4.DELETE Vechicle_rental");
        System.out.println("5.EDIT STOCKS");
        System.out.println("6.VIEW RENTED Vechicle_rentalS");
        System.out.println("7.EXIT");
        String h3=sc.next();
        if(h3.equals("1"))
        addAd();
        else if(h3.equals("2"))
        book();
        else if(h3.equals("3"))
        view();
        else if(h3.equals("4"))
        delete();
        else if(h3.equals("5"))
        edit();
        else if(h3.equals("6"))
        soldout();
        else
        welcome();
    }
    public static void addAd()
    {
        System.out.print("\033[H\033[2J");
        System.out.flush();
        System.out.println("ENTER THE Ad NAME");
        String h4=sc.next();
        System.out.println("ENTER THE ID");
        String h5=sc.next();
        System.out.println("RE-ENTER THE ID");
        String h6=sc.next();
        if(h5.equals(h6))
        {
            l.add(h4);
            l1.add(h6);
            System.out.println("\t\tAd ADDED SUCCESSFULLY");
        }
        else{
            System.out.println("ID DOESN'T MATCH");
            
        }
        System.out.println();
            System.out.println("====PRESS ENTER TO CONTINUE====");
	        sc.nextLine();
	        String s=sc.nextLine();
	        if(s.equals(""))
            Ad1();
    }
    public static void user()
    {
        System.out.print("\033[H\033[2J");
        System.out.flush();
        System.out.println("\t\tWELCOME");
        System.out.println();
        System.out.println("1.LOGIN");
        System.out.println("2.SIGN UP");
        System.out.println("3.EXIT");
        System.out.println();
        int o=sc.nextInt();
        if(o==1)
        {
            loginuser();
        }
        else if(o==2)
        {
            signupuser();
        }
        else
        {
            welcome();
        }


    }
    public static void book()
    {
        System.out.print("\033[H\033[2J");
        System.out.flush();
        System.out.println("ENTER THE Vechicle_rental NUMBER");
        String j =sc.next();
        System.out.println();
        System.out.println("ENTER THE VECHCILETYPE");
        System.out.println();
        System.out.println("1.CAR");
        System.out.println("2.BIKE");
        int j1=sc.nextInt();
        System.out.println();
        System.out.println("ENTER THE Vechicle_rental QUANTITY");
        String j2=sc.next();
        System.out.println();
        System.out.println("ENTER THE Vechicle_rental PRICE");
        String lll=sc.next();
        if(j1==1)
        {
        l2.add(j);
        l3.add("CAR");
        l4.add(j2);
        l8.add(id);
        l11.add(lll);
        id++;
        }
        else if(j1==2)
        {
        l2.add(j);
        l3.add("BIKE");
        l4.add(j2);
        l8.add(id);
        l11.add(lll);
        id++;
        }
        else{
        System.out.println("ENTER THE CORRECT TYPE");
    }
        System.out.println();
        System.out.println("====PRESS ENTER TO CONTINUE====");
        sc.nextLine();
        String s=sc.nextLine();
        if(s.equals(""))
        Ad1();
    }
    public static void view()
    {
        System.out.print("\033[H\033[2J");
        System.out.flush();
        if(l2.size()<1)
        {
            System.out.println("NOTHING TO DISPLAY");
        }
        else{
            System.out.println("VECHCILE NUMBER||  VECHCICLE TYPE   ||  Vechicle_rental QAUNTITY  ||   Vechicle_rental PRICE ");
        for(int i=0;i<l2.size();i++){
        System.out.println(   l2.get(i)+"           "+l3.get(i)+"          "+l4.get(i)+"                      "+l11.get(i));
        }
    }
System.out.println();
System.out.println("====PRESS ENTER TO CONTINUE====");
sc.nextLine();
String s=sc.nextLine();
if(s.equals(""))
Ad1();
}
public static void delete()
{
    System.out.print("\033[H\033[2J");
        System.out.flush();
    System.out.println("\t\tENTER THE BOOK ID TO BE DELETED ");
    System.out.println();
    for(int i=0;i<l8.size();i++){
    System.out.println("VECHCILE ID IS : "+l8.get(i)+"||"+" Vechicle_rental NUMBER IS : "+l2.get(i)+"||"+" Vechicle_rental TYPE IS : "+l3.get(i));
}
 int k=sc.nextInt();
 int y=l8.indexOf(k);
 l2.remove(y);
 l3.remove(y);
 l4.remove(y);
 l8.remove(y);
 System.out.println();
 System.out.println("SUCCESFULLY DELETED");
System.out.println();
System.out.println("====PRESS ENTER TO CONTINUE====");
sc.nextLine();
String s=sc.nextLine();
if(s.equals(""))
Ad1();
}
public static void edit()
{
    System.out.print("\033[H\033[2J");
        System.out.flush();
    System.out.println("\t\tWELCOME Ad");
    System.out.println();
    for(int i=0;i<l8.size();i++){
        System.out.println("BOOK ID IS : "+l8.get(i)+"||"+" BOOK NAME IS : "+l2.get(i)+"||"+"BOOK QUANTITY : "+l4.get(i)+"||"+"BOOK TYPE : "+l3.get(i)+"||"+"BOOK PRICE : "+l11.get(i));
    }
    System.out.println();
    System.out.println("1.CHANGE THE Vechicle_rental NUMBER");
    System.out.println("2.CHANGE THE Vechicle_rental COUNT");
    System.out.println("3.CHANGE THE Vechicle_rental TYPE");
    System.out.println("4.CHANGE THE Vechicle_rental PRICE");
    System.out.println("5.EXIT");
    jj=sc.nextInt();
    if(jj==1){
    edit1();
}
    else if(jj==2){
    edit1();}
    else if(jj==3){
        edit1();}
        else if(jj==4){
            edit1();}
        else
        Ad();
}
public static void edit1()
{  String edn;
    System.out.println("ENTER THE Vechicle_rental ID TO BE EDITED");
    int ed=sc.nextInt();
    int kk=l8.indexOf(ed);
    System.out.println();
    if(jj==1){
    System.out.println("ENTER THE NEW NUMBER");
    edn=sc.next();
    l2.set(kk,edn);
    }
    else if(jj==2){
        System.out.println("ENTER THE NEW COUNT");
        edn=sc.next();
        l4.set(kk,edn);
        }
        else if(jj==3)
        {
            System.out.println("ENTER THE NEW TYPE");
            edn=sc.next();
            l3.set(kk,edn);
        }
        else if(jj==4)
        {
            System.out.println("ENTER THE NEW PRICE");
            edn=sc.next();
            l11.set(kk,edn);
        }
    System.out.println();
    System.out.println("SUCCESFULLY UPDATED");
    System.out.println();
    System.out.println("====PRESS ENTER TO CONTINUE====");
    sc.nextLine();
    String s=sc.nextLine();
    if(s.equals(""))
    Ad1();
}
    static String p;
    public static void loginuser()
    {
        System.out.print("\033[H\033[2J");
        System.out.flush();
        System.out.println("ENTER THE NAME");
        p=sc.next();
        System.out.println("ENTER THE PIN");
        String p1=sc.next();
        System.out.println();
        if(l5.contains(p)&&l6.contains(p1)||p.equals("J")&&p1.equals("10"))
        {
            if(l2.size()<1)
            {
                System.out.println("NOTHING TO DISPLAY");
            }
            else{
                for(int i=0;i<l8.size();i++){
                    System.out.println("Vechicle_rental ID IS : "+l8.get(i)+"||"+" Vechicle_rental NUMBER IS : "+l2.get(i)+"||"+"Vechicle_rental QUANTITY : "+l4.get(i)+"||"+"Vechicle_rental TYPE : "+l3.get(i)+"||"+"Vechicle_rental PRICE : "+l11.get(i));
                }
                user1();
            }
        }
        else
        {
            System.out.println("PLEASE SIGNUP");
        }
        System.out.println();
        System.out.println("====PRESS ENTER TO CONTINUE====");
        sc.nextLine();
        String s=sc.nextLine();
        if(s.equals(""))
        user();
    }
    public static void signupuser()
    {
        System.out.println("\t\tWELCOME TO SIGNUP PAGE");
        System.out.println();
        System.out.println("ENTER YOUR NAME");
        String p=sc.next();
        System.out.println();
        System.out.println("ENTER THE PIN");
        String p1=sc.next();
        System.out.println();
        System.out.println("RE-ENTER THE PIN");
        String p2=sc.next();
        if(p1.equals(p2))
        {
         l5.add(p);
         l6.add(p1);
         usid++;
         l7.add(usid);
         System.out.println("ACCOUNT CREATED");
         System.out.println("YOUR ID IS : "+usid);
         System.out.println();
         System.out.println("RS.30000 IS KEPT AS HOLD FROM YOUR ACCOUNT");
         int pop=l7.indexOf(usid);
         l9.add(pop,"30000");
        }
        else
        {
            System.out.println("PIN DOESN'T MATCH");
        }
        System.out.println();
        System.out.println("====PRESS ENTER TO CONTINUE====");
        sc.nextLine();
        String s=sc.nextLine();
        if(s.equals(""))
        user();
    }
    public static void user1()
    {
        System.out.println();
        System.out.println();
        System.out.println("\t\tWELCOME "+p);
        System.out.println();
        System.out.println("1.ADD TO CART ");
        System.out.println("2.REMOVE FROM CART");
        System.out.println("3.VIEW CART");
        System.out.println("4.VIEW BALANCE");
        System.out.println("5.RETURN");
       
        System.out.println("6.EXIT");
        System.out.println();
        int y1=sc.nextInt();
        if(y1==1)
        {
            add();
        }
        else if(y1==2)
        {
            remove();
        }
        else if(y1==3)
        {
            viewcart();
        }
        else if(y1==4)
        {
            viewbalance();
        }
        else if(y1==5)
        {
            returnbook();
        }
      
        else
        {
            user();
        }
    }
        public static void add()
        {
            System.out.println("ENTER THE Vechicle_rental ID");
            int y2=sc.nextInt();
            int y3=l8.indexOf(y2);
            if(b.contains(l2.get(y3))){
                System.out.println("CANNOT RENT SAME VECHCILE");
            }else{
               b.add(l2.get(y3));
               poo=Integer.parseInt(l4.get(y3));
               poo--;
               l4.set(y3,Integer.toString(poo));
               System.out.println(poo);
            LocalDate borrow=LocalDate.now();
           
            System.out.println();
            System.out.println("VECHCILE RENTED SUCCESSFULLY");
            System.out.println();
            System.out.println("VECHCILE RENTED  ON : "+borrow);
            l10.add(String.valueOf(borrow));
            LocalDate due=borrow.plusDays(15);
            l12.add(String.valueOf(due));
            }
            System.out.println("====PRESS ENTER TO CONTINUE====");
            sc.nextLine();
            String s=sc.nextLine();
            if(s.equals(""))
            user1();
           }
    public static void remove()
           {
             System.out.println("ENTER THE BOOK ID");
            int y2=sc.nextInt();
            int y3=l8.indexOf(y2);
            b.remove(l2.get(y3));
            poo++;
            l4.set(y3,Integer.toString(poo));
            System.out.println();
            System.out.println("BOOK REMOVED SUCCESSFULLY");
            System.out.println();
            System.out.println("====PRESS ENTER TO CONTINUE====");
            sc.nextLine();
            String s=sc.nextLine();
            if(s.equals(""))
            user1();
           }
           public static void viewcart()
           {
             System.out.println("\t\t YOUR CART");
             System.out.println();
             System.out.println(b);
             System.out.println();
             System.out.println("====PRESS ENTER TO CONTINUE====");
             sc.nextLine();
             String s=sc.nextLine();
             if(s.equals(""))
             user1();
           }
          
public static void viewbalance()
{
    System.out.print("\033[H\033[2J");
    System.out.flush();
    int pop=l9.indexOf(l9.get(l8.size()-1));
    System.out.println("YOUR BALANCE IS : "+l9.get(pop));
    System.out.println();
    System.out.println("DO YOU WANT TO ADD BALANCE");
    System.out.println();
    System.out.println("1.YES");
    System.out.println("2.NO");
    String oo=sc.next();
    if(oo.equals("1"))
    {
System.out.println("ENTER THE AMOUNT");
int amount=sc.nextInt();
int jk=l8.indexOf(id);
int sum3=Integer.parseInt(l9.get(jk));
int sum4=amount+sum3;
l9.set(jk,Integer.toString(sum4));
    }
    System.out.println("====PRESS ENTER TO CONTINUE====");
    sc.nextLine();
    String s=sc.nextLine();
    if(s.equals(""))
    user1();
}
public static void returnbook()  
       {
           if(b.size()>0){
           System.out.println("ENTER THE DATE OF RETURN : ");
           String date=sc.next();
           int l121=l7.indexOf(usid);
           
           LocalDate date1=LocalDate.parse(date);
           String date2=l10.get(l121);
           LocalDate date3=LocalDate.parse(date2);
           int jj=Integer.parseInt(l4.get(l8.size()-1));
           jj++;
           l4.set(l121,Integer.toString(jj));
           if(date1.compareTo(date3)>1)
           {
               int fine=date1.compareTo(date3);
               int kop=fine-15;
               System.out.println();
               System.out.println("YOU HAVE BEEN FINED ");
               System.out.println("YOUR DUE DATE WAS ENDED "+kop+" ago");
               System.out.println();
               System.out.println("AMOUNT WILL BE REDUCED FROM YOUR  DEPOSIT ACCOUNT");
               int fine1=Integer.parseInt(l9.get(l121));
               int sorry=fine1-(fine*2);
               l9.set(l121,Integer.toString(sorry));
           }
           else{
               System.out.println("THANKS FOR RETURNING THE Vechicle_rental");
           }
               b.remove(l121);
               l10.remove(l121);
               l12.remove(l121);
               extra();
        }
        else
        {
            System.out.println("Vechicle_rental ARE  NOT BORROWED");
        }
        
           System.out.println("====PRESS ENTER TO CONTINUE====");
           sc.nextLine();
           String s=sc.nextLine();
           if(s.equals(""))
           user1();

}

public static void soldout()
{
    if(b.size()>0){
    System.out.println("\t\t SOLD OUTS");
    for(int i=0;i<l2.size();i++)
    {
        System.out.println("---------------------------------------------------------");
        System.out.println("BOOK ID : "+l8.get(i));
        System.out.println("BOOK NAME : "+l2.get(i));
        System.out.println("BOOK PRICE: "+l11.get(i));
        System.out.println("BORROWED ON : "+l10.get(i));
    }
}
else
{
    System.out.println("NO SOLDOUTS");
}
    System.out.println("====PRESS ENTER TO CONTINUE====");
    sc.nextLine();
    String s=sc.nextLine();
    if(s.equals(""))
    Ad1();
}
public static void extra()
{
    System.out.println("WHICH Vechicle_rental DID YOU RETURN ");
    System.out.println();
    System.out.println("1.CAR");
    System.out.println("2.BIKE");
    System.out.println();
    int op=sc.nextInt();
    if(op==1)
    {
        System.out.println("ENTER THE DAMAGE LABEL");
        System.out.println("1.LOW");
        System.out.println("2.MEDIUM");
        System.out.println("3.HIGH");
        System.out.println("4.NO DAMAGE");
        int opo=sc.nextInt();
        int l121=l7.indexOf(usid);
        int ex=Integer.parseInt(l9.get(l121));     
        int acho=0;
        int iii=0;
        if(opo==1)
        {
        acho=(ex*20)/100;
        iii= ex-acho;
        l9.set(l121,Integer.toString(iii));
        }
       else if(opo==2)
        {
        acho=(ex*50)/100;
        iii= ex-acho;
        l9.set(l121,Integer.toString(iii));
        }
       else if(opo==3)
        {
        acho=(ex*75)/100;
        iii= ex-acho;
        l9.set(l121,Integer.toString(iii));
        }
        else
        {
            user1();
        }
    }
    else{
        user1();

    }
    
}
    
}
