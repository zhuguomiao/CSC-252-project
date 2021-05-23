# CSC-252-project
#include <iostream>
using namespace std;

class Robot
{
private:
	int xLocation;
	int yLocation;
	bool cargoBed;
	char load;
public:
	Robot();
	int setXlocation();
	int setYlocation();
	bool setCargoBed();
	char setLoad();
	void getXlocation();
	void getYlocation();
	void getCargoBed();
	void getLoad();
};

// Add the code for the data field functions

// Getter and Setters
Robot::Robot()
{
	xLocation = 0; 
	yLocation = 0; 
}
int Robot::setXlocation()
{
	return xLocation; 
}
int Robot::setYlocation()
{
	return  yLocation;
}
bool Robot::setCargoBed()
{
	return cargoBed;
}
char Robot::setLoad()
{
	return load;
}
void Robot::getXlocation()
{
	this->xLocation = xLocation;
}
void Robot::getYlocation()
{
	this->yLocation = yLocation; 
}
void Robot::getCargoBed()
{
	this->cargoBed = cargoBed;
}
void Robot::getLoad()
{
	this->load = load;
}
*/


int main()
{

}
