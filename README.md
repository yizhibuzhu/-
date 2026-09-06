# -
int main()
{
	int n;
	scanf("%d", &n);
	//遍历
	int cont = 1;
	for (int i = 1;i < n;i++){
		cont *= 10;
	}
	//t为消耗品
	int t = cont;
	while (t < cont * 10) {
		int cishu = t;
		int sum = 0;
		int a;
		//cishu是消耗品
			while(cishu>0){
				a == cishu % 10;
				cishu /= 10;
				int c = 1;
				for (int b=0 ;b < n;b++) {
					c *= a;
				}
				sum += c;
			}
			if (sum == t) {
				printf("%d", t);
			}
			t++;
	}
	return 0;
}
