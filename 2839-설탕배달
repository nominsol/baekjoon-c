#include<stdio.h>

int mul_five(int n) {
	if (n % 5 == 0)
		return 1;
	else
		return 0;
}

int mul_three(int n) {
	if (n % 3 == 0)
		return 1;
	else
		return 0;
}

int main() {
	int N;
	int result = 0;

	scanf("%d", &N);

	while (!mul_five(N)) {
		if (N < 3)
			break;
		N -= 3;
		result += 1;

	}
	if (N != 0) {
		result += N / 5;
		N %= 5;
	}
	if (result == 0 || (N != 0)) {
		result = -1;
	}
	printf("%d\n", result);

	return 0;
}
