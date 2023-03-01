#include <cstdlib>
#include <iostream>
#include <string>

using namespace std;

int main() {

	string folder;
	int    choice;

	cout << "Choose an option:\n1: Zip folder\n2: Unzip folde\n>"; cin >> choice;

	switch (choice)
	{
	case 1: {
		cout << "Enter folder name\n>"; cin >> folder;

		string query = "zip zipped_folder " + folder;
		system(query.c_str());
		break;
	}
	case 2: {
		cout << "Enter name of archive\n>"; cin >> folder;

		string query = "unzip zipped_folder.zip -d unzipped_folder";
		system(query.c_str());
		break;
	}
	default:
		cout << "Wrong option";
	}
	return 0;
}
