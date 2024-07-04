[java.pdf](https://github.com/user-attachments/files/16093301/java.pdf)

[Java lab programs.pdf](https://github.com/user-attachments/files/16100487/Java.lab.programs.pdf)


import java.util. Scanner;

public class Salary {

public static void main(String[] args) {

double sala;

double hou, trans, ta;

double gross, net;

Scanner inp=new Scanner (System.in);

System.out.print("Enter Basic Salary ");

sala=inp.nextDouble();

hou = 15* sala;

trans=.25 * sala;

ta=03* sala;

gross = (hou + trans + sala);

net = gross-ta;

System.out.println("The gross pay is: " + gross);

System.out.println("the net pay is:" +net);
}
}

