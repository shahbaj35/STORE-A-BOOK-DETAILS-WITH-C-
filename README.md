# STORE-A-BOOK-DETAILS-WITH-C-
Write a  C++ Program to Maintain Book Records using File Handling using File Handling. Here’s simple Program to Maintain Book Records using File Handling in C++ Programming Language.

Example Program in C++ Using file handling to perform following operations:


1)      add new record

2)      View all records

3)      Delete particular record

4)      Search record

5)      Update record



#include<iostream>
#include<stdio.h>
#include<fstream>
#include<iomanip>
#include<string.h>
using namespace std;

int menu();
class Book
{
      private:
              int bookid;
              char title[20];
              float price;
      protected:
                int allotbookid();
                void showheader();
      public:
             void getbook();
             void showbook();
             void addbook();
             void viewbook();
             void searchbook();
             void deletebook();
             void modifybook();
}
