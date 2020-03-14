# BIM Development Diploma | Project 01 : Assignment Solver
This Project was for better understanding the C# Fundamentals under the instruction of Eng. Mostafa Emad It is basically a solver for the three parts of assignment 2


            #region solvernavigator
            Console.WriteLine("Welcome To BIM Software Diploma | Assignment No.2 Solver");
            Console.WriteLine("Please Press Enter to Start");
            Console.ReadLine();
        /*
        This is the start of the Solver Navigator
        The transporter moves the user through the parts of the assignement by his own selection
        */
        navigator:
            Console.WriteLine("Hello, I am the Assignment solver navigator");
            Console.WriteLine("Please Select the part of the assignment you want to check");
            Console.WriteLine("(Part1) Mathematical Operators");
            Console.WriteLine("(Part2) Conditional Statement ");
            Console.WriteLine("(Part3) Loops");
            Console.WriteLine("(0) Exit from the solver");
            Console.WriteLine("Choose (1) or (2) or (3) or (0)");
            int o1 = int.Parse(Console.ReadLine());
            if (o1 == 1)
            {
                goto part1;
            }
            if (o1 == 2)
            {
                goto part2;
            }
            if (o1 == 3)
            {
                goto part3;
            }
            if (o1 == 0)
            {
                goto part0;
            }
        #endregion
        #region PartOne
        // ###################### Assignment No.2.1.1 ###################### //
        part1:
            Console.WriteLine("Assignment No.2.1.1");
            Console.WriteLine("Please Enter The First Number");
            int x = int.Parse(Console.ReadLine());
            Console.WriteLine("Please Enter The Second Number");
            int y = int.Parse(Console.ReadLine());
            int z = x + y;
            Console.WriteLine("So Their Sum Equals " + z);
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.1.2 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.1.2");
            Console.WriteLine("Please Enter The Circle's Radius");
            int r = int.Parse(Console.ReadLine());
            double area1 = 3.14  *r*r;
            Console.WriteLine("So The Area Of The Circle equals " + area1);
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.1.3 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.1.3");
            Console.WriteLine("Please Enter The Length");
            int l = int.Parse(Console.ReadLine());
            Console.WriteLine("Please Enter The Width");
            int w = int.Parse(Console.ReadLine());
            double area2 = l * w;
            Console.WriteLine("So The Area Of The Rectangle equals " + area2);
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.1.4 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.1.4");
            Console.WriteLine("Please Enter The Triangle's Base");
            int b1 = int.Parse(Console.ReadLine());
            Console.WriteLine("Please Enter The Triangle's Height");
            int h1 = int.Parse(Console.ReadLine());
            double area3 = b1 * h1 * 0.5;
            Console.WriteLine("So The Area Of The Triangle equals " + area3);
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.1.5 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.1.5");
            Console.WriteLine("Please Enter The First Number");
            int n1 = int.Parse(Console.ReadLine());
            Console.WriteLine("Please Enter The Second Number");
            int n2 = int.Parse(Console.ReadLine());
            int sum = n1 + n2;
            int sub = n1 - n2;
            int mul = n1 * n2;
            int div = n1 / n2;
            Console.WriteLine("So After Performing all the Mathematical Operations on your two numbers");
            Console.WriteLine("Sum = " + sum);
            Console.WriteLine("Subtraction = " + sub);
            Console.WriteLine("Multiplication = " + mul);
            Console.WriteLine("Div = " + div);
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.1.6 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.1.6");
            Console.WriteLine("Please Enter The Number you want to know its reminder over 2");
            int r1 = int.Parse(Console.ReadLine());
            int rm = r1 % 2;
            Console.WriteLine("The Reminder = " + rm);
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.1.7 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.1.7");
            Console.WriteLine("Please Enter The Number you want to See it's multiplication table");
            int m1 = int.Parse(Console.ReadLine());
            int counter = 0;
            loopstart:
            counter += 1;
            if (counter <= 10) 
            {
                Console.WriteLine(m1 + " x " + counter + " = " + m1 * counter);
                goto loopstart;
            }
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.1.8 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.1.8");
            Console.WriteLine("Please Enter Five numbers");
            int a1 = int.Parse(Console.ReadLine());
            int a2 = int.Parse(Console.ReadLine());
            int a3 = int.Parse(Console.ReadLine());
            int a4 = int.Parse(Console.ReadLine());
            int a5 = int.Parse(Console.ReadLine());
            int average = (a1 + a2 + a3 + a4 + a5) / 5;
            Console.WriteLine("Their Average equals " + average );
            Console.WriteLine("============= Ended Succesfully =============");
            goto navigator;
        #endregion
        #region PartTwo
        // ###################### Assignment No.2.2.1 ###################### //
        part2:
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.2.1");
            Console.WriteLine("Please Enter The Number you want to be checked");
            int z1 = int.Parse(Console.ReadLine());
            if (z1 > 0) 
            {
                Console.WriteLine("The Number Is Postive");
            }
            else if (z1<0)
            {
                Console.WriteLine("The Number Is Negative");
            }
            else
            {
                Console.WriteLine("The Number is ZERO, Neither Postive Nor Negative");
            }
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.2.2 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.2.2");
            Console.WriteLine("Please Enter The First Number");
            int k1 = int.Parse(Console.ReadLine());
            Console.WriteLine("Please Enter The Second Number");
            int k2 = int.Parse(Console.ReadLine());
            if (k1==k2)
            {
                Console.WriteLine("The Two Numbers are EQUAL");
            }
            else
            {
                Console.WriteLine("The Two Numbers aren't Equal");
            }
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.2.3 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.2.3");
            Console.WriteLine("Please Enter The First Number");
            int j1 = int.Parse(Console.ReadLine());
            Console.WriteLine("Please Enter The Second Number");
            int j2 = int.Parse(Console.ReadLine());
            if (j1>j2)
            {
                Console.WriteLine("The First Number is bigger than the Second Number");
            }
            else if (j2>j1)
            {
                Console.WriteLine("The Second Number is bigger than the First Number");

            }
            else
            {
                Console.WriteLine("The Two Numbers are equal");

            }
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.2.4 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.2.4");
            Console.WriteLine("Please Enter The Number you want to check");
            int numb1 = int.Parse(Console.ReadLine());
            if(numb1%2 == 0)
            {
                Console.WriteLine("The Number Is Even");
            }
            else
            {
                Console.WriteLine("The Number Is Odd");
            }
                  Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.2.5 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.2.5");
            Console.WriteLine("Please Enter The Number 10");
            int num10 = int.Parse(Console.ReadLine());
            if (num10 == 10)
            {
                Console.WriteLine("The Number Is Correct, Thank you");
            }
            else
            {
                Console.WriteLine("The Number Isn't Correct");
            }
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.2.6 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.2.6");
            Console.WriteLine("Please Enter Three values for a triangle angles");
            int angle1 = int.Parse(Console.ReadLine());
            int angle2 = int.Parse(Console.ReadLine());
            int angle3 = int.Parse(Console.ReadLine());
            if (angle1+angle2+angle3 == 180)
            {
                Console.WriteLine("The Angles you entered does form a triangle");
            }
            else
            {
                Console.WriteLine("The Angles you entered DOESNOT form a triangle");
            }
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.2.7 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.2.7");
            Console.WriteLine("Please Enter The Grade of the student");
            int grade = int.Parse(Console.ReadLine());
            if (grade < 65 && grade >= 50)
            {
                Console.WriteLine("The Student Status is PASS");
            }
            else if (grade < 75 && grade >= 65)
            {
                Console.WriteLine("The Student Status is GOOD");
            }
            else if (grade < 85 && grade >= 75)
            {
                Console.WriteLine("The Student Status is VERY GOOD");
            }
            else if (grade >= 85)
            {
                Console.WriteLine("The Student Status is EXCELLENT");
            }
            else
            {
                Console.WriteLine("The Student Status is FAIL");
            }
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.2.8 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.2.8");
            Console.WriteLine("Please Enter The Grade letter in CAPITALS please");
            string grade2 = Console.ReadLine();
            switch (grade2)
            {
                case "P":
                    Console.WriteLine("The Grade is PASS");
                    break;
                case "F":
                    Console.WriteLine("The Grade is FAIL");
                    break;
                case "G":
                    Console.WriteLine("The Grade is GOOD");
                    break;
                case "V":
                    Console.WriteLine("The Grade is VERY GOOD");
                    break;
                case "E":
                    Console.WriteLine("The Grade is EXCELLENT");
                    break;

            }
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.2.9 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.2.9");
            Console.WriteLine("Please Enter The desired month number");
            int month = int.Parse(Console.ReadLine());
            switch (month)
            {
                case 1:
                    Console.WriteLine("January Have 31 Days");
                    break;
                case 2:
                    Console.WriteLine("February Have 28 Days");
                    break;
                case 3:
                    Console.WriteLine("March Have 31 Days");
                    break;
                case 4:
                    Console.WriteLine("April Have 30 Days");
                    break;
                case 5:
                    Console.WriteLine("May Have 31 Days");
                    break;
                case 6:
                    Console.WriteLine("June Have 30 Days");
                    break;
                case 7:
                    Console.WriteLine("July Have 31 Days");
                    break;
                case 8:
                    Console.WriteLine("August Have 31 Days");
                    break;
                case 9:
                    Console.WriteLine("September Have 30 Days");
                    break;
                case 10:
                    Console.WriteLine("October Have 31 Days");
                    break;
                case 11:
                    Console.WriteLine("November Have 30 Days");
                    break;
                case 12:
                    Console.WriteLine("December Have 31 Days");
                    break;
            }
            Console.WriteLine("============= Ended Succesfully =============");
            // ###################### Assignment No.2.2.10 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.2.10");
            Console.WriteLine("The Equation is aX^2 + bX + c = 0 ");
            Console.WriteLine("Please Enter The the value a");
            int eqa = int.Parse(Console.ReadLine());
            Console.WriteLine("Please Enter The the value b");
            int eqb = int.Parse(Console.ReadLine());
            Console.WriteLine("Please Enter The the value c");
            int eqc = int.Parse(Console.ReadLine());
            if ( (eqb * eqb)-(4*eqa*eqc) < 0 )
            {
                Console.WriteLine("There are no real roots for your equation");
            }
            if ((eqb * eqb) - (4 * eqa * eqc) == 0)
            {
                Console.WriteLine("There is only one real root for your equation");
                double root1 = (eqb * -1) / (2 * eqa);
                Console.WriteLine("The Answer is "+ root1);
            }
            if ((eqb * eqb) - (4 * eqa * eqc) > 0)
            {
                Console.WriteLine("There are two real roots for your equation");
                double root2 = ((eqb * -1) + Math.Sqrt((eqb * eqb) - (4 * eqa * eqc))) / (2 * eqa);
                double root3 = ((eqb * -1) - Math.Sqrt((eqb * eqb) - (4 * eqa * eqc))) / (2 * eqa);
                Console.WriteLine("The Answers is " + root2 + " , " + root3);
            }
            goto navigator;
        #endregion
        #region PartThree
        part3:

            // ###################### Assignment No.2.3.1 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.3.1");
            Console.WriteLine("Press enter to allow me to write from 1 to 100 using FOR loop ");
            Console.ReadLine();
            for (int t = 1; t<101; t++)
            {
                Console.WriteLine(t);
            }
            Console.WriteLine("============= Ended Succesfully =============");

            // ###################### Assignment No.2.3.2 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.3.2");
            Console.WriteLine("Press enter to allow me to write from 1 to 100 using WHILE loop ");
            Console.ReadLine();
            int q = 1;
            while (q<101)
            {
                Console.WriteLine(q);
                q++;
            }
            Console.WriteLine("============= Ended Succesfully =============");

            // ###################### Assignment No.2.3.3 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.3.3");
            Console.WriteLine("Press enter a number");
            int so1 = int.Parse(Console.ReadLine());
            int sum10 = 0;
            while (so1 % 2 == 0)
            {
                Console.WriteLine("Please Re-enter a number");
                so1 = int.Parse(Console.ReadLine());
                sum10 = sum10 + so1;
            }
            Console.WriteLine("The Sum of the even numbers you entered is " + sum10);
            Console.WriteLine("============= Ended Succesfully =============");

            // ###################### Assignment No.2.3.4 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.3.4");
            Console.WriteLine("Press enter to allow me to calculate the sum of even numbers until 10");
            Console.ReadLine();
            int sum11 = 0;
            for (int v =0; v<11; v++)
            {
                if (v%2==0)
                {
                    sum11 = sum11 + v;
                }
            }
            Console.WriteLine("The sum of the even numbers until 10 is " + sum11);
            Console.WriteLine("============= Ended Succesfully =============");

            // ###################### Assignment No.2.3.5 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.3.5");
            Console.WriteLine("Press enter to allow me to calculate the sum of numbers divisible by 3 until 100");
            Console.ReadLine();
            int sum12 = 0;
            for (int po = 0; po < 101; po++)
            {
                if (po % 3 == 0)
                {
                    sum12 = sum12 + po;
                }
            }
            Console.WriteLine("The sum of the numbers divisible by 3 until 100 is " + sum12);
            Console.WriteLine("============= Ended Succesfully =============");

            // ###################### Assignment No.2.3.6 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.3.6");
            Console.WriteLine("Press enter a number so i can calculate its cube for you");
            int cube = int.Parse (Console.ReadLine());
            Console.WriteLine("The cube of the number equals " + cube * cube * cube);
            Console.WriteLine("============= Ended Succesfully =============");

            // ###################### Assignment No.2.3.7 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.3.7");
            Console.WriteLine("Press enter to allow me to find how many even and odd numbers between 1 and 100");
            Console.ReadLine();
            int even = 0;
            int odd = 0;
            for (int pu = 1; pu < 101; pu++)
            {
                if (pu % 2 == 0)
                {
                    even++;
                }
            }
            odd = 100 - even;
            Console.WriteLine("The number of even numbers is " + even);
            Console.WriteLine("The number of odd numbers is " + odd);
            Console.WriteLine("============ Ended Succesfully =============");

            // ###################### Assignment No.2.3.8 ###################### //
            Console.WriteLine("Please Press Enter to Proceed");
            Console.ReadLine();
            Console.WriteLine("Assignment No.2.3.8");
            Console.WriteLine("Press enter three angles of a triangle");
            int ang1 = int.Parse(Console.ReadLine());
            int ang2 = int.Parse(Console.ReadLine());
            int ang3 = int.Parse(Console.ReadLine());
            for (int oi = 0; oi < 4; oi++)
            {
                if (ang1 + ang2 + ang3 == 180)
                {
                    Console.WriteLine("Correct Input, The Sum equals 180");
                    goto finish;
                }
                Console.WriteLine("Press Re-enter a CORRECT three angles of a triangle");
                int triesnum = 3 - oi;
                if (triesnum == 0)
                {
                    goto fail;
                }
                Console.WriteLine("You only have " + triesnum + " tries left");
                ang1 = int.Parse(Console.ReadLine());
                ang2 = int.Parse(Console.ReadLine());
                ang3 = int.Parse(Console.ReadLine());
            }
        fail:
            Console.WriteLine("Sorry, You ran out of tries");
            finish:
            Console.WriteLine("============ Ended Succesfully =============");
            goto navigator;

        #endregion
        #region EndSolver
        part0:
                Console.WriteLine("============= Ended Succesfully =============");
                Console.WriteLine("===================================================================");
                Console.WriteLine("===================================================================");
                Console.WriteLine("===================================================================");
                Console.WriteLine("============= The Assignment Solver has ended its job =============");
                Console.WriteLine("===================================================================");
                Console.WriteLine("===================================================================");
                Console.WriteLine("===================================================================");
                Console.WriteLine("============= Done By : Mohamed Adel Essa =============");
                Console.WriteLine("===================================================================");
                Console.WriteLine("===================================================================");
                Console.WriteLine("===================================================================");
                Console.WriteLine("============= Under The Instruction Of : Eng. Mostafa Emad =============");
                Console.WriteLine("Please Press Enter to Exit");
                Console.ReadLine();
            #endregion
        }
    }
    }

