# ATM_ONLINE_FROM_PRATEEK
#include <iostream>
#include <cstring>
#include <iomanip>
//#include <stdio.h>
#include <string.h>

void showbalance(double balance);
double deposit();
double withdraw(double balance);
char help3();
char help4();

int main()
{
    int balance = 0;
    int choice = 0;
    int pin,pin2;
    char str[25],str1[25];
    int help2[10];
    std::string help;
    
    std::cout << "________________________________\n";
    std::cout << "WELCOME_TO_PRATEEK'S_ONLINE_ATM\n";
    std::cout << "___________CALIFORNIA___________                      \n";
    std::cout << "                       \n";
    std::cout << "PRATEEK'S HEAD OFFICE TOLL_NO - 20616838\n";
    std::cout << "                       \n";
    std::cout << "ENTER YOUR ATM PIN:";
    std::cin >> pin;
    
    do
    {
        std::cin.clear();
        fflush(stdin);
        std::cout << "\n*************************\n";
        std::cout << "Please Enter Your Choice: \n";
        std::cout << "*************************\n";
        std::cout << "1. SHOW BALANCE\n";
        std::cout << "2. DEPOSIT MONEY\n";
        std::cout << "3. WITHDRAW MONEY\n";
        std::cout << "4. [24/7]HELP_SUPPORT\n";
        std::cout << "5. CHANGE ATM PIN\n";
        std::cout << "6. EXIT\n";
        std::cin >> choice;
        
        switch(choice)
        {
            case 1: showbalance(balance);
            break;
            case 2: balance = balance + deposit();
                    showbalance(balance);
            break;
            case 3: balance = balance - withdraw(balance);
                    showbalance(balance);
            break;
            case 4: help3();
                    //help4();
                    break;
                
                case 5:
                std::cout << "\nPLEASE ENTER YOUR OLD PIN TO COUNTINUE:";
                std::cin >> pin2;
    if(pin2==pin)
    {
    std::cout << "Enter your new (4_Digit) Pin:";
    std::cin >> str;
    std::cout << "Conform Your New (4_Digit) Pin:";
    std::cin >> str1;
    if(strcmp(str,str1)==0)
    {
        std::cout << "\n\nYOUR ATM PIN CHANGED SUCCESFULLY\n";
    }
    else
    {
        std::cout << "\n\nPin not matched\nPLEASE TRY AGAIN\n\n";
    }
    }
    else
    {
        std::cout << "INCORRECT PIN\nTRY AGAIN\n";
    }
    break;
            case 6: std::cout << "THANK_YOU_FOR_VISITING_PRATEEK'S_E-ATM\nCEO & MD - PRATEEK KORATALA\nHEAD QUARTERS-USA,CALIFORNIA-53013";
            break;
            default: std::cout << "SORRY_502_BAD_GATEWAY_PLEASE_TRY_AGAIN_\n";
            break;
        }
    }while(choice != 6);
    
    return 0;
}
void showbalance(double balance)
{
    std::cout << "YOUR BALANCE IS $" << std::setprecision(2) << std::fixed << balance << '\n';
    std::cout << "                            \n";
}
double deposit()
{
    double amount;
    
    std::cout << "ENTER THE AMOUNT TO DEPOSIT:";
    std::cin >> amount;
    std::cout << "                            ";
    
    if(amount<1)
    {
        std::cout <<"SORRY PLEASE TRY AGAIN WITH VALID INPUT\n";
        return 0;
    }
    else
    {
        return amount;
    }
    
    return amount;
}
double withdraw(double balance)
{
    double amount = 0;
    
    std::cout << "ENTER AMOUNT TO WITHDRAW:";
    std::cin >> amount;
    std::cout << "                            ";
    if(amount > balance)
    {
        std::cout << "SORRY INSUFISIENT BALANCE\n";
        return 0;
    }
    else if(amount < 1)
    {
        std::cout << "SORRY PLEASE TRY AGAIN WITH VALID INPUT\n";
        return 0;
    }
    else
    {
        return amount;
    }
    
    return amount;
}
char help3()
{
    char help2[10];
    //std::string help2[344];
    std::cout << "SORRY_FOR_THE_INCONVENINCE\nPLEASE DESCRIBE YOUR ISSUE:";
    //std::getline(std::cin,help2[344]);
    std::cin >> help2;
    std::cout << "WE UNDERSTOOD YOUR PROBLEM\nOUR TEAM WILL CONTACT YOU WITHIN 24HRS\n";
    int help3[10];
    std::cout << "PLEASE ENTER YOUR (10_Digit) MOBILE NUMBER:";
    std::cin >> help3[10];
    std::cout << "THANK YOU\nOUR TEAM WILL CONTACT YOU WITHIN 10min\n";

}
char help4()
{
    int help3[10];
    std::cout << "PLEASE ENTER YOUR (10_Digit) MOBILE NUMBER:";
    std::cin >> help3[10];
    std::cout << "THANK YOU\nOUR TEAM WILL CONTACT YOU WITHIN 24HRS\n";
}char help;
    //std::string help;
    
    std::cout << "WELCOME_TO_PRATEEK'S_ATM\n";
    std::cout << "______CALIFORNIA______                      \n";
    std::cout << "                       \n";
    std::cout << "ENTER YOUR ATM PIN:";
    std::cin >> pin;
    
    do
    {
        std::cout << "\n*************************\n";
        std::cout << "Please Enter Your Choice: \n";
        std::cout << "*************************\n";
        std::cout << "1. SHOW BALANCE\n";
        std::cout << "2. DEPOSIT MONEY\n";
        std::cout << "3. WITHDRAW MONEY\n";
        std::cout << "4. HELP_SUPPORT\n";
        std::cout << "5. CHANGE PIN\n";
        std::cout << "6. EXIT\n";
        std::cin >> choice;
        
        switch(choice)
        {
            case 1: showbalance(balance);
            break;
            case 2: balance = balance + deposit();
                    showbalance(balance);
            break;
            case 3: balance = balance - withdraw(balance);
                    showbalance(balance);
            break;
            case 4: std::cout << "SORRY_FOR_THE_INCONVENINCE\nPLEASE DESCRIBE YOUR ISSUE:";
                std::cin >> help;
                std::cout << "WE UNDERSTOOD YOUR PROBLEM\nOUR TEAM WILL CONTACT YOU WITHIN 24HRS\n";
            break;
                
                case 5:char str[20],str1[20];
    printf("Prateek's Password manager[5.7.1]vr");
    printf("\nenter your new Password:");
    std::cin >> (str);
    printf("\nConfirm new password:");
    std::cin >> (str1);
    if(strcmp(str,str1)==0)
    {
        printf("\nPassword changed\n");
    }
    else
    {
        printf("\nPassword not matched\nPLEASE TRY AGAIN\n");
    }
    break;
            case 6: std::cout << "THANK_YOU_FOR_VISITING_PRATEEK'S_E-ATM\nHead Quatars-USA,CALIFORNIA-132";
            break;
            default: std::cout << "SORRY_502_BAD_GATEWAY_PLEASE_TRY_AGAIN_\n";
            break;
        }
    }while(choice != 6);
    
    return 0;
}
void showbalance(double balance)
{
    std::cout << "YOUR BALANCE IS $" << std::setprecision(2) << std::fixed << balance << '\n';
    std::cout << "                            \n";
}
double deposit()
{
    double amount;
    
    std::cout << "ENTER THE AMOUNT TO DEPOSIT:";
    std::cin >> amount;
    std::cout << "                            ";
    
    if(amount<1)
    {
        std::cout <<"SORRY PLEASE TRY AGAIN WITH VALID INPUT\n";
        return 0;
    }
    else
    {
        return amount;
    }
    
    return amount;
}
double withdraw(double balance)
{
    double amount = 0;
    
    std::cout << "ENTER AMOUNT TO WITHDRAW:";
    std::cin >> amount;
    std::cout << "                            ";
    if(amount > balance)
    {
        std::cout << "SORRY INSUFISIENT BALANCE\n";
        return 0;
    }
    else if(amount < 1)
    {
        std::cout << "SORRY PLEASE TRY AGAIN WITH VALID INPUT\n";
        return 0;
    }
    else
    {
        return amount;
    }
    
    return amount;
}
