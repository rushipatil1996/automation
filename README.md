# automation
int n=10;
	for(int i=1;i<=n;i++)//outer loop for no. of row(n)
		{
		for (int j=2*(n-i);j>=1;j--) {
			System.out.print(" ");
		}
		for (int j=1;j<=i;j++) {
			System.out.print("*");
			System.out.print(" ");
		}
		System.out.println();//ending line after each row
	}
}
//note-this is confidantial for suchita//
