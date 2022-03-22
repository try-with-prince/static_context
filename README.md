class New{
static int a;
 public void display(){
  System.out.println("in Test1 class");
 }
}
 class News{
  public static void main(String arg[])
{


System.out.println(New.a);	//jab main call hoga after loading static methods, class, and static varriable load hoga  then runtime jab execution ho rha tab whenever jvm finds the anyclassname 1stly it will create the static context for it so now it appens the value of a.



  System.out.println("in Test class");
  //Test1 t = new Test1();
  //t.display();
 }
}        
