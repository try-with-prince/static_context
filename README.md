class New{
    static int s;
    public void display(){
        System.out.println("in  hu Test1 class");
    }
}
public class News{
   static int a=19;
    public static void main(String arg[])
    {

        System.out.println(a);	//jab main call hoga after loading static methods, class, and static varriable load hoga  then runtime jab execution ho rha tab whenever jvm finds the anyclassname 1stly it will create the static context for it so now it appens the value of a.
//ye ishi class me h isliye direct call ho rha .
System.out.println(New.s);//dusri class se static varriable access karne ke liye ya to class se access kro, ya class object ke reffrence se
New f1=new New();

        System.out.println(f1.s);
        System.out.println("in Test class");


        New o1=new New();
        o1.display();
        //System.out.println(o1.display());

        Test1 t = new Test1();
        t.display();

    }
}
