# StudentGradeCalculator.java
https://www.programiz.com/online-compiler/8ODw9GQjyKMPc
ublic class StudentGradeCalculator {

    public static void main(String[] args) {
        // Define student names and grades directly in the code
        String[] studentNames = {"Alice", "Bob", "Charlie"};
        int[] studentGrades = {85, 90, 75};  // Fixed grades
        
        // Print the student names and grades
        System.out.println("Student Grades:");
        double total = 0;
        for (int i = 0; i < studentNames.length; i++) {
            System.out.println(studentNames[i] + ": " + studentGrades[i]);
            total += studentGrades[i];
        }

        // Calculate the average grade
        double average = total / studentGrades.length;
        
        // Print the average grade
        System.out.printf("Average Grade: %.2f\n", average); // Display the average
    }
}
