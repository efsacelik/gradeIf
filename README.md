# gradeIf
Calculating academic grades.
package patikaAcademy;

import java.util.Scanner;

public class notHesaplamIf {

	public static void main(String[] args) {

		int math, physics, chem, bio, eng;
		double average;

		Scanner scanner = new Scanner(System.in);

		System.out.println("Enter your Math grade");
		math = scanner.nextInt();

		System.out.println("Enter your Physics grade");
		physics = scanner.nextInt();

		System.out.println("Enter your Chemistry grade");
		chem = scanner.nextInt();

		System.out.println("Enter your Biology grade");
		bio = scanner.nextInt();

		System.out.println("Enter your English grade");
		eng = scanner.nextInt();

		average = (math + physics + chem + bio + eng) / 5;

		if (average <= 55) {
			System.out.println("You failed");
		} else {
			System.out.println("You passed");
		}
		System.out.println("Your grade is :"+ average);
	}

}
