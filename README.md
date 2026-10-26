# ACTIVIT1
MOBILE DEVE
 STUDENT GRADE COMPUTATION

void main() {
  String name = 'Student';
  double grade1 = 89.90;
  double grade2 = 90.72;
  double grade3 = 95.67;
  int subjects = 3;
  bool pass = true;
  double sum;

  sum = grade1 + grade2 + grade3;
  double average = sum / subjects;
  bool Pass = average > 75;

  print('name: $name');
  print('average: $average');
  print('Does student passed? $Pass');
}
