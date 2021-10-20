- 👋 Hi, I’m @lyx020914
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me lipan

<!---
lyx020914/lyx020914 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->#include<stdio.h>
double fact (int n);
int main(void)
{
	int i,n;
	double result,sum;
	sum=0;
	scanf("%d",&n);
	for(i=1;i<=n;i++){
		result=fact(i);
		sum=sum+result;
	}
	printf("sum=%If",sum);
	return 0;
}
double fact(int n)
{
	int i;
	double product;
	product=1;
	for(i=1;i<=n;i++)
	product=product*i; 
	return product;
}
