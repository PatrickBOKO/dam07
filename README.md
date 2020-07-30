# dam07
using System;

namespace Revision_Coding
{
    class Program
    {
        static void Main(string[] args)
        {




            // ODD NUM ALIGN 

            /*
             * 
             * int count = 0; 

            for (int i = 1; i < 100; i += 2)
            {
                count += 1;
                Console.Write(String.Format("{0,5}",i.ToString()));
                if (count % 10 == 0)
                    Console.Write("\n");
            }

            */ 





            /* int uval = Convert.ToInt32(Console.ReadLine());

            bool checkP = true;
            for (int i = 2; i <= uval / 2; i++)
            {
                if (uval % i == 0)
                {
                    checkP = false;
                    break;
                }
            }
            if (checkP)
            {

                Console.WriteLine(uval + " is a Prime Number.");
                int f_val = uval;
                for (int v = 1; v < uval; v++)
                {
                    f_val = f_val * v;
                }
                Console.WriteLine("The Number you entered is : " + uval + "Factorial is " + f_val);
            }
            else
                Console.WriteLine(uval + " is not a Prime Number.");

            */




            /// DATE FORMAT APP


            /*        
            {
                class Program
                {
                    static int Main()
                    {
                        DateTime date = new DateTime(2013,6, 23);
                        Console.WriteLine("Some Date Formats : ");
                        Console.WriteLine("Date and Time:  {0}", date);
                        Console.WriteLine(date.ToString("yyyy-MM-dd"));
                        Console.WriteLine(date.ToString("dd-MMM-yy"));
                        Console.WriteLine(date.ToString("M/d/yyyy"));
                        Console.WriteLine(date.ToString("M/d/yy"));
                        Console.WriteLine(date.ToString("MM/dd/yyyy"));
                        Console.WriteLine(date.ToString("MM/dd/yy"));
                        Console.WriteLine(date.ToString("yy/MM/dd"));
                        Console.Read();
                        return 0;
                    }
                }

            */



            ///  DIAMOND SHAPE CODE


            /*
            int i,j,r;
   
	            Console.Write("\n\n");
                Console.Write("Display the pattern like diamond:\n");
                Console.Write("-----------------------------------");
                Console.Write("\n\n");     
   
               Console.Write("Input number of rows (half of the diamond) :");
               r = Convert.ToInt32(Console.ReadLine());   
               for(i=0;i<=r;i++)
               {
                 for(j=1;j<=r-i;j++)
                 Console.Write(" ");
                 for(j=1;j<=2*i-1;j++)
                 Console.Write("*");
                 Console.Write("\n");
               }
 
               for(i=r-1;i>=1;i--)
               {
                 for(j=1;j<=r-i;j++)
                 Console.Write(" ");
                 for(j=1;j<=2*i-1;j++)
                   Console.Write("*");
                 Console.Write("\n");
               }

            */



            /*
             * GROSSE EQUIPE ... :)           COMPLETE 
             * 
             *  4.1. ; √
                4.2. Void√
                4.3. const√
                4.4. double √
                4.5. Console.ReadLine();√
                4.6. Console.ReadLine();√
                4.7. hourly * hours; √
                4.8. <=√
                4.9. Else√
                4.10. net √
                4.11. {1}√
                4.12. Hours√
                4.13. {0,10}",√
                4.14. ToString("C"));√
                4.15. }√
             */


            /*   STUDENT MARKS CALCULATION 
             *   int r, m1, m2, m3, t; √√
                 float p; √
                 string n; 
             *   t = m1 + m2 + m3; √
                 p = t / 3.0f; √
                 Console.WriteLine("Total : " + t);
                 Console.WriteLine("Percentage : " + p);
                 if (p >= 35 && p < 50)
                 {
                 Console.WriteLine("Grade is C");
                 }
                 if (p >= 50 && p <= 60)
                 {
                 Console.WriteLine("Grade is B");
                 }
                 if (p > 60 && p <= 80)
                 {
                 Console.WriteLine("Grade is A");
                 }
                 if (p > 80 && p <= 100)
                 {
                 Console.WriteLine("Grade is A+");
                 }
                 Console.ReadLine();



            private void button2_Click(object sender, EventArgs e)
             {
             this.Hide();
            Programming 3A
            Page 12 of 12
             Form1 sp = new Form1();
             sp.ShowDialog();
             this.Close();




            */





        }





    }









































































    /*
     * 
     * 
     * 1.1 Programming Logic – Programming logic involves executing the various statements and
        procedures in the correct order to produce the desired results. √√
        1.2 Debugging – Debugging is the process of removing all syntax errors and logical errors from a
        program. √√
        1.3 Computer program – is also known as software and is a set of instructions that tells a computer
        what to do. √√
        1.4 Compiler – A Compiler is a program which translates high-level language statements into
        machine code. √√
        1.5 Programming Language – A programming language is used to write computer programs
        1.6 An identifier – is the name of a program component such as a variable, class, or method. √√
        1.7 Machine language – Machine language is the most basic circuitry-level language. √√
        1.8 Classes – an abstract representation of an object, its attributes (properties), and its behaviors
        (methods). √√
        1.9 Encapsulation –a black box technique in which an object’s attributes and methods are packaged
        in a cohesive unit that can be used as an undivided entity. √√
        1.10 Application software – Application software is the programs that allow users to complete tasks. 
     * 
     * 
     * 
     * 1.1. Whitespace- is any combination of spaces, tabs, and carriage returns (blank lines). You use
        whitespace to organize your program code and make it easier to read; it does not affect your
        program.√ √

        1.2. Debugging a program is the process of removing all syntax and logical errors from the
        program. √√

        1.3. Variable -named computer memory locations that hold values that might vary. √√

        1.4. Polymorphism is the ability to create methods that act appropriately depending on the context.
        √√

        1.5. A verbatim identifier is an identifier with an @ prefix. √√

        1.6. An Integrated Development Environment (IDE) is a program development environment that
        allows you to select options from menus or by clicking buttons. An IDE provides such helpful
        features as colour coding and automatic statement completion. √√

        1.7. The Solution Explorer in the IDE provides the means to view and manage project files and
        settings. √√

        1.8. The Properties window in the IDE provides the means to configure properties and events on
        controls in your user interface. √√

        1.9. Short-circuit evaluation is the C# feature in which parts of an AND or OR expression are
        evaluated only as far as necessary to determine whether the entire expression is true or false.
        √√

        1.10. A step value is the amount by which a loop control variable is altered, especially in a for loop. 

     * 2.1. How is C# different from other languages? (4)
        Unlike other programming languages, C# allows every piece of data to be treated as an object and to
        consistently employ the principles of object-oriented programming. √√
        C# provides constructs for creating components with properties, methods, and events, making it an
        ideal language for twenty-first century programming, where building small, reusable components is
        more important than building huge, stand-alone applications. √√

        2.2. List and describe 3 types of comments used in C# (6)
         Line comments start with two forward slashes (//) and continue to the end of the current line. Line
        comments can appear on a line by themselves, or at the end of a line following executable code.
        √√
         Block comments start with a forward slash and an asterisk (/*) andend with an asterisk and a
        forward slash (*-/). Block comments can appear on a line by themselves, on a line before
        executable code, or after executable code.When a comment is long, block comments can extend
        across as many lines as needed. √√
         C# also supports a special type of comment used to create documentation within a program. These
        comments, called XML-documentation format comments, use a special set of tags within angle
        brackets(< >). (XML stands for Extensible Markup Language.) You will learn more about this type
        of comment as you continue your study of C#.√√


        2.3. How would one go about using a class that’s part of a namespace? (3)
        When you need to repeatedly use a class from the same namespace, you can shorten the statements
        you type by adding a clause that indicates a namespace that contains the class. √You indicate a
        namespace with a using clause, or using directive√ for example; if you type using System; prior to the
        class definition, the compiler knows to use the System namespace when it encounters the Console
        class. √

        2.4. How is the CompareTo() method used in C#? (3)
        The CompareTo() method uses a string, a dot, and the method name. √When it returns 0, the two
        strings are equivalent; √ when it returns a positive number, the first string is greater than the second;
        and when it returns a negative value, the first string is less than the second. √


        2.5. Define and list 9 Integral data types respectively. (10)
        Integral types store whole numbers. √The nine integral types are byte, sbyte, short, ushort, int, uint,
        long, ulong, and char. The first eight always represent whole numbers,and the ninth type, char, is
        used for characters like ‘A’ or ‘a’.

        Differentiate between the following:
        3.1. Application and non-application classes. (3)
        Classes that contain a Main() method are application classes. √Classes that do not contain a Main()
        method are non-application classes. √ Non application classes provide support for other classes. √

        3.2. Prefix and Postfix operator (3)
        The prefix increment operator (++ before a variable) increases the Variable’s value by 1 and then
        evaluates it. √The postfix increment operator (++ after a variable) evaluates a variable and then adds
        1 to it. √√

        3.3. Implicit Cast and Explicit Cast (3)
        Implicit cast is the automatic transformation that occurs when a value is assigned to a type with
        higher precedence. √
        Explicitly means purposefully. An explicit cast purposefully assigns a value to a different data type; it
        involves placing the desired result type in parentheses followed by the variable or constant to be
        cast. √√

        A constant is a variable whose value cannot be changed throughout its lifetime: √√√
        Constants have the following characteristics:
        They must be initialized when they are declared, and once a value has been assigned, it can never
        be overwritten. √√
        Programming 3A
        Page 4 of 12
        The value of a constant must be computable at compile time. √√
        Constant make your programs easier to read by replacing magic numbers and stings with readable
        names whose values are easy to understand. √√√
        Constants make your programs easier to modify √√
        Constant make it easier to avoid mistakes in your program. √√


        2.1.1 Integer Types
        C# supports a variety of integer types also known as whole number types. All integer-type variables can
        be assigned values in decimal or in hex notation. The latter require the 0x prefix:
        Examples of integer types are: byte, int, short, and long. √√

        2.1.2 Floating Point type
        A floating-point number contains decimal positions. √
        Floating-point data types are:

        1. Float - Can hold up to 7 significant digits of accuracy. Put an F after a number to make
        it a float. √

        2. Double - Can hold 15 or 16 significant digits of accuracy. Put a D after it to make it a
        double (default). √

        3. Decimal - Can hold 28 or 29 significant digits but a smaller range. Suitable for financial
        and monetary calculations. Put an M after it to make it a decimal. √

        2.1.3 The Boolean type
        The C# bool type is used to contain Boolean values of either true or false. √√

        2.2.4 The character type
        For storing the value of a single character, C# supports the char data type 
        
        Literals of type char are signified by being enclosed in single quotes, for example ‘A’. If we try to
        enclose a character in double quotes, the compiler will treat this as a string and throw an error. √√

        2.2.5 The string type
        C-sharp acknowledges the keyword string, which is translated under the hood to the .NET
        System.string class. √
        Example: String strOne = “Hello”; √
        A string is a reference type regardless of the demonstrated assignment above. √























                /////////////////////////////////////////////////////////////////////////////////////////////////


            ///   PAPER ROCK SCISORS ...
            ///   

            /* 


    try
            {

                int computerNo = random.Next(1, 4); String computerchoice = "";  // 1 ==> rock  2 ==> papaer  3 ==> scissors
                char userChoice = char.ToLower(txtinput.Text[0]);

                Boolean play = true;

                while (play == true)
                {

                    if (computerNo == 1)
                        computerchoice = "rock";
                    else if (computerNo == 2)
                        computerchoice = "paper";
                    else if (computerNo == 3)
                        computerchoice = "scissors";


                    if (computerNo == 1 && userChoice == 'r')
                        MessageBox.Show("The computer has chosen:  " + computerchoice + "\n Its a tie");
                    else if (computerNo == 1 && userChoice == 'p')
                        MessageBox.Show("The computer has chosen:  " + computerchoice + "\n You won");
                    else if (computerNo == 1 && userChoice == 's')
                        MessageBox.Show("The computer has chosen:  " + computerchoice + "\n You lost");

                    if (computerNo == 2 && userChoice == 'r')
                        MessageBox.Show("The computer has chosen:  " + computerchoice + "\n You won");
                    else if (computerNo == 2 && userChoice == 'p')
                        MessageBox.Show("The computer has chosen:  " + computerchoice + "\n It's a tie");
                    else if (computerNo == 2 && userChoice == 's')
                        MessageBox.Show("The computer has chosen:  " + computerchoice + "\n You lost");

                    if (computerNo == 3 && userChoice == 'r')
                        MessageBox.Show("The computer has chosen:  " + computerchoice + "\n You won");
                    else if (computerNo == 3 && userChoice == 'p')
                        MessageBox.Show("The computer has chosen:  " + computerchoice + "\n You lost");
                    else if (computerNo == 3 && userChoice == 's')
                        MessageBox.Show("The computer has chosen:  " + computerchoice + "\n It's a tie");

                    play = false;
                }
            }
            catch (Exception ex)
            {
                MessageBox.Show("Exception caught: " +  ex );
            }
        }






   
                ///////// ///////////////////////////////////////////////////////////////////////////////////////////

                   

                /////  SIMPLE CALCULATOR :::
                ///


    using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace SimpleCalculator
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        int Total;
        int val1, val2;
       


        private void btnExit_Click(object sender, EventArgs e)
        {
            this.Close();
        }

        private void rbtnAdd_CheckedChanged(object sender, EventArgs e)
        {
            btnSubstract.Visible = false;
            btnTimes.Visible = false;
            btnAdd.Visible = true; 
        }

        private void rbtnSubstract_CheckedChanged(object sender, EventArgs e)
        {
            btnAdd.Visible = false;
            btnTimes.Visible = false;
            btnSubstract.Visible = true; 

        }

        private void rbtnTimes_CheckedChanged(object sender, EventArgs e)
        {
            btnAdd.Visible = false;
            btnSubstract.Visible = false;
            btnTimes.Visible = true; 
        }

        private void btnAdd_Click(object sender, EventArgs e)
        {
            try
            {
                val1 = Convert.ToInt32(txtval1.Text); val2 = Convert.ToInt32(txtval2.Text);
                Total = val1 + val2;
                txtval1.Clear(); txtval2.Clear();
                MessageBox.Show("The Total is : " + Total);

            }
            catch(Exception ex)
            {
                MessageBox.Show("Error "+ ex);
            }
            

        }

        private void btnTimes_Click(object sender, EventArgs e)
        {
            try
            {
                val1 = Convert.ToInt32(txtval1.Text); val2 = Convert.ToInt32(txtval2.Text);
                Total = val1 * val2;
                txtval1.Clear(); txtval2.Clear();
                MessageBox.Show("The Total is : " + Total);

            }
            catch (Exception ex)
            {
                MessageBox.Show("Error " + ex);
            }
        }

        private void btnSubstract_Click(object sender, EventArgs e)
        {
            try
            {
                val1 = Convert.ToInt32(txtval1.Text); val2 = Convert.ToInt32(txtval2.Text);
                Total = val1 - val2;
                txtval1.Clear(); txtval2.Clear();
                MessageBox.Show("The Total is : " + Total);

            }
            catch (Exception ex)
            {
                MessageBox.Show("Error " + ex);
            }
        }
    }
}



                  ////////////////////////////////////////////////////////////////////////////////////////////////////////////////




                *****  ////  PRIME NUMBERS 
                *
                *
                *
                *Console.WriteLine("Enter a Number : ");

            try
            {
                 //Console.WriteLine(4%2);
                int uservalue = Convert.ToInt32(Console.ReadLine());

                bool isPrime = true;
                for (int i = 2; i <=uservalue / 2; i++)
                {
                    if (uservalue % i == 0)
                    {
                        isPrime = false;
                        break;
                    }
                }
                if (isPrime && uservalue!=0)
                {

                    Console.WriteLine(uservalue + " is a Prime Number.");
                    int factorial_value = uservalue;
                    for (int v = 1; v < uservalue; v++)
                    {
                        factorial_value = factorial_value * v;
                    }
                    Console.WriteLine("\nThe Number you entered is : " + uservalue + ". And it's factorial is " + factorial_value);
                }
                else
                    Console.WriteLine(uservalue + " is not a Prime Number.");

            }

            catch( Exception ex)
            {
                Console.WriteLine("Error caught: {0} ", ex); 
            }

            Console.ReadKey();














                ///////  ////////////////////////////////////////////////////////////////////////////////////////////////////////

                ///////    ATM  PROGRAM .....


                ///////
                ///

                    using System;
using System.Dynamic;
using System.Runtime.CompilerServices;
using System.Runtime.InteropServices.WindowsRuntime;

namespace Atm_Program
{
    class Program
    {
        static void Main(string[] args)
        {



            String user_code = ""; 
            Boolean passed = true, ShowMainMenu=false; String Next_key = "";


            /////
            ///

            Console.WriteLine("This is an ATM. \nPlease Enter Your Pin code .");
            user_code = Get_Numeric("");
            Random Amount = new Random();

            Double Balance = Amount.Next(1000, 1000000);


            while (passed == true)
            {
                


                if (user_code == "0" )
                {
                    Console.WriteLine("\nThe value you entered is : {0}, Press Enter to continue..", user_code);
                    Console.ReadKey(); ShowMainMenu = true; 


                    while (ShowMainMenu == true)
                    {
                        Console.WriteLine("\n\n***********************Welcome To ATM Service.***********************");

                        Console.WriteLine("1. Check Balance  \n\n2. Withdraw Cash  \n\n3. Deposit Cash  \n\n4. Quit ");
                        Console.WriteLine("\n\n\n\n**********************************************************************\n\nEnter your Choice:");

                        String Selected_no = Get_Numeric(""); ShowMainMenu = false;


                        if (Selected_no == "1")
                        {

                            Console.WriteLine("\nACCOUNT LOGIN : \n\nYour Account Balance is: R {0} ", Balance);
                            Console.WriteLine("\nPress Enter to Go Back to Main Menu..");
                            Console.ReadKey(); 
                            ShowMainMenu = true; 

                        }
                        else if (Selected_no == "2")
                        {
                            Console.WriteLine("\nACCOUNT LOGIN : \n\nEnter specified amount to Withdraw And press Enter:");
                            Double withdrawalAmount = Convert.ToDouble(Get_Numeric(""));
                            Balance -= withdrawalAmount;
                            Console.WriteLine("\n\nTransaction Completed successfully ! \nPress Enter to Go Back to Main Menu..");
                            Console.ReadKey();
                            ShowMainMenu = true;
                        }
                        else if (Selected_no == "3")
                        {
                            Console.WriteLine("\nACCOUNT LOGIN : \n\nEnter Deposit Amount And press Enter: ");
                            Double depositAmount = Convert.ToDouble(Get_Numeric(""));
                            Balance += depositAmount;
                            Console.WriteLine("\n\nTransaction Completed successfully ! \nPress Enter to Go Back to Main Menu..");
                            Console.ReadKey();
                            ShowMainMenu = true;
                        }
                        else if (Selected_no == "4")
                        {
                            Console.WriteLine("\n\n******Thank you for banking with us. \nExiting System...");
                            System.Environment.Exit(-1);
                        }
                        else
                            Console.WriteLine("\nPlease Select a valid number. Press Enter to Go Back to Main Menu..");
                            Console.ReadKey();
                            ShowMainMenu = true;



                        //Console.WriteLine(Selected_no);
                        //Console.WriteLine("Mr S :) "); 

                        // break;

                    }
                }

                while (user_code != "0")
                {
                    Console.WriteLine("\nThe value you entered is : {0}, Press Enter to continue..", user_code);
                    Console.ReadKey(); 
                    Console.WriteLine("\nYou typed the wrong pin : " + user_code + "\nEnter the correct Pin Number and press Enter \nOr type 4 to Quit ");
                    Next_key = Get_Numeric("");

                    if (Next_key == "4")
                        System.Environment.Exit(-1);
                    else if (Next_key == "0")
                        user_code = "0";
                    else
                        user_code = Next_key; 
                    break;


                }



            }








            Console.ReadKey();


            //Console.ReadKey(); 
        }


        public static String  Get_Numeric(String num)
        {
            ConsoleKeyInfo Info_chr;
            double val = 0;
            //string num = "";
            do
            {
                Info_chr = Console.ReadKey(true);
                if (Info_chr.Key != ConsoleKey.Backspace)
                {
                    bool control = double.TryParse(Info_chr.KeyChar.ToString(), out val);
                    if (control)
                    {
                        num += Info_chr.KeyChar;
                        Console.Write(Info_chr.KeyChar);
                    }
                }
                else

                {
                    if (Info_chr.Key == ConsoleKey.Backspace && num.Length > 0)
                    {
                        num = num.Substring(0, (num.Length - 1));
                        Console.Write("\b \b");
                    }
                }
            }
            while (Info_chr.Key != ConsoleKey.Enter);
             
            return num; 
        }

       

    }
}








            ////////////////////////////////////////////////////////////////////////////////////////////////////////////
            ///

    .           ///   MUTLI FUNCTION CALC 


    using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace Multifunction_Calculator
{
    public partial class Form1 : Form
    {

        Double FirstNum, SecondNum, Result;
        String Sign;


        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            txtOutput.Text = "";
        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }

        private void btnClose_Click(object sender, EventArgs e)
        {
            this.Close();
        }

        private void btn1_Click(object sender, EventArgs e)
        {
            if (txtOutput.Text == "0" && txtOutput.Text != null)
            {
                txtOutput.Text = "1";
            }
            else
            {
                txtOutput.Text = txtOutput.Text + "1";
            }
        }

        private void btn2_Click(object sender, EventArgs e)
        {
            if (txtOutput.Text == "0" && txtOutput.Text != null)
            {
                txtOutput.Text = "2";
            }
            else
            {
                txtOutput.Text = txtOutput.Text + "2";
            }
        }

        private void btn3_Click(object sender, EventArgs e)
        {
            if (txtOutput.Text == "0" && txtOutput.Text != null)
            {
                txtOutput.Text = "3";
            }
            else
            {
                txtOutput.Text = txtOutput.Text + "3";
            }
        }

        private void btn4_Click(object sender, EventArgs e)
        {
            if (txtOutput.Text == "0" && txtOutput.Text != null)
            {
                txtOutput.Text = "4";
            }
            else
            {
                txtOutput.Text = txtOutput.Text + "4";
            }
        }

        private void btn5_Click(object sender, EventArgs e)
        {
            if (txtOutput.Text == "0" && txtOutput.Text != null)
            {
                txtOutput.Text = "5";
            }
            else
            {
                txtOutput.Text = txtOutput.Text + "5";
            }
        }

        private void btn6_Click(object sender, EventArgs e)
        {
            if (txtOutput.Text == "0" && txtOutput.Text != null)
            {
                txtOutput.Text = "6";
            }
            else
            {
                txtOutput.Text = txtOutput.Text + "6";
            }
        }

        private void btn7_Click(object sender, EventArgs e)
        {
            if (txtOutput.Text == "0" && txtOutput.Text != null)
            {
                txtOutput.Text = "7";
            }
            else
            {
                txtOutput.Text = txtOutput.Text + "7";
            }
        }

        private void btn8_Click(object sender, EventArgs e)
        {
            if (txtOutput.Text == "0" && txtOutput.Text != null)
            {
                txtOutput.Text = "8";
            }
            else
            {
                txtOutput.Text = txtOutput.Text + "8";
            }
        }

        private void btn9_Click(object sender, EventArgs e)
        {
            if (txtOutput.Text == "0" && txtOutput.Text != null)
            {
                txtOutput.Text = "9";
            }
            else
            {
                txtOutput.Text = txtOutput.Text + "9";
            }
        }

        private void btnPlus_Click(object sender, EventArgs e)
        {
            FirstNum = Convert.ToDouble(txtOutput.Text);
            txtOutput.Text = "0";
            Sign = "+";

        }

        private void btnMinus_Click(object sender, EventArgs e)
        {
            FirstNum = Convert.ToDouble(txtOutput.Text);
            txtOutput.Text = "0";
            Sign = "-";
        }

        private void btnTimes_Click(object sender, EventArgs e)
        {
            FirstNum = Convert.ToDouble(txtOutput.Text);
            txtOutput.Text = "0";
            Sign = "*";
        }

        private void btnDivide_Click(object sender, EventArgs e)
        {
            FirstNum = Convert.ToDouble(txtOutput.Text);
            txtOutput.Text = "0";
            Sign = "/";
        }

        private void btnBack_Click(object sender, EventArgs e)
        {
            //String input = txtOutput.Text;

            if (txtOutput.Text.Length > 1)
            {
                txtOutput.Text = txtOutput.Text.Substring(0, txtOutput.Text.Length - 1);
            }
            else
            {
                txtOutput.Text = "0";
            }

        }

        private void btnC_Click(object sender, EventArgs e)
        {
            FirstNum = 0;
            SecondNum = 0;
            txtOutput.Text = "0";
        }

        private void btnexpo_Click(object sender, EventArgs e)
        {
            FirstNum = Convert.ToDouble(txtOutput.Text);
            txtOutput.Text = "0";
            Sign = "^"; 


        }

        private void btnSqrt_Click(object sender, EventArgs e)
        {
            FirstNum = Convert.ToDouble(txtOutput.Text);
            txtOutput.Text = (Math.Pow(FirstNum,2)).ToString(); 

        }

        private void btnEqual_Click(object sender, EventArgs e)
        {
            SecondNum = Convert.ToDouble(txtOutput.Text);

            if (Sign == "+")
            {
                Result = (FirstNum + SecondNum);
                txtOutput.Text = Convert.ToString(Result);
                FirstNum = Result;
            }
            if (Sign == "-")
            {
                Result = (FirstNum - SecondNum);
                txtOutput.Text = Convert.ToString(Result);
                FirstNum = Result;
            }
            if (Sign == "*")
            {
                Result = (FirstNum * SecondNum);
                txtOutput.Text = Convert.ToString(Result);
                FirstNum = Result;
            }

            if (Sign == "/")
            {
                if (SecondNum == 0)
                {
                    txtOutput.Text = "Cannot divide by zero";

                }
                else
                {
                    Result = (FirstNum / SecondNum);
                    txtOutput.Text = Convert.ToString(Result);
                    FirstNum = Result;
                }
            }

            if (Sign == "^")
            {
                
                {
                    Result =  Math.Pow(FirstNum, SecondNum);
                    txtOutput.Text = Convert.ToString(Result);
                    FirstNum = Result;
                }
            }


        }




        private void btn0_Click(object sender, EventArgs e)
        {           
                

            if (txtOutput.Text == "0" && txtOutput.Text != null)
            {
                txtOutput.Text = "0";
            }
            else
            {
                txtOutput.Text = txtOutput.Text + "0";
            }

        }

        private void btnPeriod_Click(object sender, EventArgs e)
        {
            txtOutput.Text = txtOutput.Text + ".";
        }
    }
}








        */



}




