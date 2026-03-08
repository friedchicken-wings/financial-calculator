#include <stdio.h>

int questions(char* money){
        int monthly; 
       printf("What is your monthly %s?\n", money);
       scanf("%d", &monthly);
       return monthly;
    } 
int percent(int bill, int income){
    int percent = ((float)bill/income) * 100;
    return (int)percent;
}
int main(){
    int income = questions ("income");
    int rent = questions ("rent");
    int utilities = questions ("utilities");
    int groceries = questions ("groceries");
    int transportation = questions ("transportation");
    
    printf("\nMonthly Breakdown\n");
    printf("rent: %d%% of income\n", percent(rent, income));
    printf("utilities: %d%% of income\n", percent(utilities, income));
    printf("groceries: %d%% of income\n", percent(groceries, income));
    printf("transportation: %d%% of income\n", percent(transportation, income));
    
    return 0;
    }