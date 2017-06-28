echo "# ggT" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Rosheng/ggT.git
git push -u origin master// UseRational.java (Version .1-3)


import java.io.*;


class UseRational {


   public static void main(String[] args) throws Exception {


	// Definitionen
	InputStreamReader isr = new InputStreamReader(System.in);
	BufferedReader keyboard = new BufferedReader(isr);


	Rational r;


	// Dialog
	System.out.println();
	System.out.print("Geben Sie den Zaehler ein: ");
	int a = Integer.parseInt(keyboard.readLine());
	System.out.print("Geben Sie den Nenner ein: ");
	int b = Integer.parseInt(keyboard.readLine());
	System.out.println();


	// Rational-Objekt erzeugen
	r = new Rational(a,b);


	// Methodenaufrufe
	System.out.println(r.toString());   	  // Bruch ausgeben
	System.out.println(r.toStringReduced());  // Bruch gekuerzt ausgeben


	System.out.println();
   }
}


// UseRational.1-3
