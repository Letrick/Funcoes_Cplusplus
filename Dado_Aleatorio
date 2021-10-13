#include <iostream>

#include <cstdlib>
#include <ctime>


int dado () {
	srand(time(NULL));

	return rand() % 6 + 1; 

	
}



int main () {

	int num = dado();
	int vezes1 = 0;
	int vezes2 = 0;
	int vezes3 = 0;
	int vezes4 = 0;
	int vezes5 = 0;
	int vezes6 = 0;
	

	for (int i = 0; i <=100000; i++){
	
	

		int num = dado();

		std::cout << num;
		
		
		if (num == 1){
		vezes1++;			
		}
		
		if (num == 2){
		vezes2++;			
		}
		if (num == 3){
		vezes3++;			
		}
		if (num == 4){
		vezes4++;			
		}
		if (num == 5){
		vezes5++;			
		}
		if (num == 6){
		vezes6++;			
		}
	
}
	
	std::cout << "\n O numero 1 apareceu: " << vezes1;
	std::cout << "\n O numero 2 apareceu: " << vezes2;
	std::cout << "\n O numero 3 apareceu: " << vezes3;
	std::cout << "\n O numero 4 apareceu: " << vezes4;
	std::cout << "\n O numero 5 apareceu: " << vezes5;
	std::cout << "\n O numero 6 apareceu: " << vezes6;

	
	
	
}







