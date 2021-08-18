#include <iostream>

int main() {
  
  int dog_age;//declaring the variable that 
              //stores the age of your dog
 std::cout << "Type Your Dogs age: ";
 std::cin >> dog_age;
 std::cout << "\n";
  int early_years; //to findout earlyhuman years
  int later_years; //to findout dogs past 2 
                   //human years
  int human_years;//to calculate total human 
                  //years of the dog

early_years = 21;//early years of dog(<=2)
  //is comsidered to be 21 human years
later_years = (dog_age - 2)*4;
//each year of a dog after 2 is considered to be //4 human years
human_years = later_years + early_years ;
//finding total dog years
std::cout << "Your Dog age is: " << human_years <<" years old in Human Years.\n";

}
