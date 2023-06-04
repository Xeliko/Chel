# C++

Homework 08.06.2023
#include <iostream>
using namespace std;

//Zadaniye 1

//class Circle {
//private:
//    double radius;
//
//public:
//    Circle(double radius) {
//        this->radius = radius;
//    }
//
//    bool operator==(const Circle& other) const {
//        return this->radius == other.radius;
//    }
//
//    bool operator>(const Circle& other) const {
//        return this->radius > other.radius;
//    }
//
//    Circle& operator+=(double value) {
//        this->radius += value;
//        return *this;
//    }
//
//    Circle& operator-=(double value) {
//        this->radius -= value;
//        return *this;
//    }
//
//    double getRadius() const {
//        return this->radius;
//    }
//
//    void setRadius(double radius) {
//        this->radius = radius;
//    }
//};
//
//int main() {
//    Circle circle1(5.0);
//    Circle circle2(3.0);
//
//    
//    if (circle1 == circle2) {
//        std::cout << " Radiusi okrujnostey ravni" << endl;
//    }
//    else {
//        std::cout << "Radiusi okrujnostey ne ravni" << endl;
//    }
//
//    
//    if (circle1 > circle2) {
//        std::cout << "Pervaya okrujnost dlinee vtoroy" << endl;
//    }
//    else {
//        std::cout << "Pervaya okrujnost ne dlinee vtoroy" << endl;
//    }
//
//    
//    circle1 += 2.0;
//    cout << "Radius pervoy okrujnosti posle uvelecheniya: " << circle1.getRadius() << endl;
//
//    circle2 -= 1.0;
//    cout << "Radius pervoy okrujnosti posle umensheniya:" << circle2.getRadius() << endl;
//
//    return 0;
//}
//
//


//Zadaniye 2


//class Airplane {
//private:
//    string type;
//    int passengers;
//
//public:
//    Airplane(string type, int passengers) {
//        this->type = type;
//        this->passengers = passengers;
//    }
//
//    bool operator==(const Airplane& other) const {
//        return this->type == other.type;
//    }
//
//    Airplane& operator++() {
//        ++passengers;
//        return *this;
//    }
//
//    Airplane& operator--() {
//        if (passengers > 0) {
//            --passengers;
//        }
//        return *this;
//    }
//
//    bool operator>(const Airplane& other) const {
//        return this->passengers > other.passengers;
//    }
//
//    int getMaxPassengers() const {
//        return passengers;
//    }
//};
//
//int main() {
//    Airplane airplane1("Boeing 737", 150);
//    Airplane airplane2("Airbus A320", 180);
//
//    
//    if (airplane1 == airplane2) {
//        cout << "Tipi samoletov ravni" << endl;
//    }
//    else {
//        cout << "Tipi samoletov ne ravni" << endl;
//    }
//
//    
//    ++airplane1;
//    cout << "Passajiri v samolete 1: " << airplane1.getMaxPassengers() << endl;
//
//    
//    --airplane2;
//    cout << "Passajiri v samolete 2:  " << airplane2.getMaxPassengers() << endl;
//
//    
//    if (airplane1 > airplane2) {
//        cout << "Perviy samolet vmeshayet bolshe passajorov" << endl;
//    }
//    else {
//        cout << "vtoroy samolet vmeshayet bolshe passajorov" << endl;
//    }
//
//    return 0;
//}
