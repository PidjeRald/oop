#include<iostream>
#include<string>
#include<fstream>
using namespace::std;

class Double {
	string pCel;
	string pDrob;
public:
	Double(string cel = "0", string drob = "0") {
		pCel = cel;
		pDrob = drob;
	}
	Double(const Double& other) {
		this->pCel = other.pCel;
		this->pDrob = other.pDrob;
	}
	~Double() {
		pCel = {};
		pDrob = {};
	}



	Double plus(Double b) {
		string slag1, slag2;
		slag1 = this->pCel + "." + this->pDrob;
		slag2 = b.pCel + "." + b.pDrob;
		double sum = stod(slag1) + stod(slag2);
		string cel = to_string(sum).erase(to_string(sum).find('.'));
		string drob = to_string(sum).erase(0, to_string(sum).find('.') + 1);
		if (drob.empty()) {
			Double temp(cel);
			return temp;
		}
		Double temp(cel, drob);
		return temp;
	}
	Double minus(Double b) {
		string slag1, slag2;
		slag1 = this->pCel + "." + this->pDrob;
		slag2 = b.pCel + "." + b.pDrob;
		double raz = stod(slag1) - stod(slag2);
		string cel = to_string(raz).erase(to_string(raz).find('.'));
		string drob = to_string(raz);
		drob.erase(0, drob.find('.') + 1);
		if (drob.empty()) {
			Double temp(cel);
			return temp;
		}
		Double temp(cel, drob);
		return temp;
	}
	Double proizv(Double b) {
		string slag1, slag2;
		slag1 = this->pCel + "." + this->pDrob;
		slag2 = b.pCel + "." + b.pDrob;
		double proizv = stod(slag1) * stod(slag2);
		string cel = to_string(proizv).erase(to_string(proizv).find('.'));
		string drob = to_string(proizv);
		drob.erase(0, drob.find('.') + 1);
		if (drob.empty()) {
			Double temp(cel);
			return temp;
		}
		Double temp(cel, drob);
		return temp;
	}
	Double delenie(Double b) {
		string slag1, slag2;
		slag1 = this->pCel + "." + this->pDrob;
		slag2 = b.pCel + "." + b.pDrob;
		if (slag2 == "0.0") {
			Double temp;
			return temp;
		}
		double delenie = stod(slag1) / stod(slag2);
		string cel = to_string(delenie).erase(to_string(delenie).find('.'));
		string drob = to_string(delenie);
		drob.erase(0, drob.find('.') + 1);
		if (drob.empty()) {
			Double temp(cel);
			return temp;
		}
		Double temp(cel, drob);
		return temp;
	}



	bool operator == (const Double& other) {
		return ((this->pCel == other.pCel) && (this->pDrob == other.pDrob));
	}
	bool operator != (const Double& other) {
		return !((this->pCel == other.pCel) && (this->pDrob == other.pDrob));
	}


	bool operator > (const Double& other) {
		if (this->pCel > other.pCel)
			return 1;
		else
			if ((this->pCel == other.pCel) && (this->pDrob > other.pDrob))
				return 1;
		return 0;
	}
	bool operator >= (const Double& other) {
		if (this->pCel > other.pCel)
			return 1;
		else
			if ((this->pCel == other.pCel) && (this->pDrob >= other.pDrob))
				return 1;
		return 0;
	}


	bool operator < (const Double& other) {
		if (this->pCel < other.pCel)
			return 1;
		else
			if ((this->pCel == other.pCel) && (this->pDrob < other.pDrob))
				return 1;
		return 0;
	}
	bool operator <= (const Double& other) {
		if (this->pCel < other.pCel)
			return 1;
		else
			if ((this->pCel == other.pCel) && (this->pDrob <= other.pDrob))
				return 1;
		return 0;
	}



	Double& operator = (const Double& other) {
		this->pCel = other.pCel;
		this->pDrob = other.pDrob;
		return *this;
	}



	friend ostream& operator << (ostream& os, const Double& other);
	friend istream& operator >> (istream& os, Double& other);
};

ostream& operator << (ostream& os, const Double& other)
{
	os << other.pCel << "." << other.pDrob;
	return os;
}

istream& operator >> (istream& is, Double& other)
{
	is >> other.pCel >> other.pDrob;
	return is;
}

int main() {
	int choice;
	Double a, b;
	cout << "a = " << a << "\nb = " << b << "\n\n1.summa\n2.raznost\n3.proizvedenie\n4.delenie\n5.sravnit( == || != )\n6.sravnit(  > || <= )\n7.sravnit( >= || <  )\n8.izmenit a\n9.izmenit b\n10.a = b\n11.vivesti a,b\n12.vihod\n\n";
	do {
		cin >> choice;
		switch (choice) {
		case 1:
			cout << "summa = " << a.plus(b) << endl;
			break;
		case 2:
			cout << "raznost = " << a.minus(b) << endl;
			break;
		case 3:
			cout << "proizvedenie = " << a.proizv(b) << endl;
			break;
		case 4:
			cout << "delenie = " << a.delenie(b) << endl;
			break;
		case 5:
			if (a == b)
				cout << "a = b\n";
			else
				cout << "a != b\n";
			break;
		case 6:
			if (a > b)
				cout << "a > b\n";
			else
				cout << "a <= b\n";
			break;
		case 7:
			if (a >= b)
				cout << "a >= b\n";
			else
				cout << "a < b\n";
			break;
		case 8:
			cout << "a = ";
			cin >> a;
			break;
		case 9:
			cout << "b = ";
			cin >> b;
			break;
		case 10:
			a = b;
			break;
		case 11:
			cout << "a = " << a << "\nb = " << b << endl;
			break;
		default:
			break;
		}
	} while (choice != 12);
	return 0;
}
