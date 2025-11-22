using System;
class Alif
{
    public void horny()
    {
        Console.WriteLine("Alif Is horny");
    }
}
class beforSleep : Alif
{
    public void night()
    {
        Console.WriteLine("he Masterbated ");
    }
}
class Program
{
    public static void Main(string[] args)
    {
        beforSleep t1=new beforSleep();
        t1.horny();t1.night();
        
    }
}
