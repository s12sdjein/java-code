# java-code
import java.io.File;
public class Main{
    public static void main(String[] args) {
        File myfile=new File("Assignment_Timecard.xlsx - Google Sheets.txt");
        System.out.println("data in the file is");
        int day=0;
        char name=0;
        char position=0;
        int hour=0;
        if(day==7){
            System.out.println(name);
            System.out.println(position);

        }
        if(hour<10 & hour>1){
            System.out.println(name);
            System.out.println(position);
        }
        if(hour>14){
            System.out.println(name);
            System.out.println(position);
        }


    }
}
