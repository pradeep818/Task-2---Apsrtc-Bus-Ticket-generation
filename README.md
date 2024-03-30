namespace pradeep;
class system
{
    public static void Main(string[] args)
    {
        int s = 40;
        Console.WriteLine("          ***Bus Ticket Generation***");
        Console.Write("DEPO : ");
        String Depo=Console.ReadLine();
        Console.Write("Vehicle no : ");
        String vehicle=Console.ReadLine();
        Console.Write("Date : ");
        String Date=Console.ReadLine();
        Console.Write("No of Adults : ");
        int n=Convert.ToInt32(Console.ReadLine());
        Console.Write("Source :");
        String Source=Console.ReadLine();
        Console.Write("destination :");
        String destination=Console.ReadLine();
        Console.WriteLine("          ***APSRTC***");
        Console.WriteLine();
        Console.WriteLine("DEPO :" + Depo);
        Console.WriteLine("Vehicle no : "+vehicle);
        Console.WriteLine("              Date: " + Date);
        Console.WriteLine("    " + Source + "---> " + destination);
        Console.WriteLine("A :"+n+"x"+s+"="+n*s);
        Console.WriteLine("         -Not Transferable-");
    }
}
