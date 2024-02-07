// This is my first program.

    public class ExamGrade
    {
        public static void main (String[] args)
        {
            
                
              int exam1 = 100;
              int exam2 = 90;
              int exam3 = 80;
              int exam4 = 87;
              int exam5 = 93;
                    
                    int SumOfExamScores = exam1+exam2+exam3+exam4+exam5;    // If you use double or float it will output a decimal. 
                    int PercentageOfExamScores = SumOfExamScores/5;
                            
            char letter;
            
                letter = 'A';
                letter = 'B';
                letter = 'C';
                letter = 'D';
                letter = 'F';
                
                        if (PercentageOfExamScores >=90)
                            { letter = 'A';}
                        if (PercentageOfExamScores >=80 && PercentageOfExamScores <90)
                            { letter = 'B';}
                        if (PercentageOfExamScores >=70 && PercentageOfExamScores <80)
                            { letter = 'C';}
                        if (PercentageOfExamScores >=60 && PercentageOfExamScores <70)
                            { letter = 'D';}
                        if (PercentageOfExamScores <60)
                            { letter = 'F';}
                      
                                                      // Tell the user what will be expected of them when the program begins.
                    
                                                       // The user took 5 exams and will need to enter each score for the exam for a average. 
                
                System.out.println ("You are going to enter marks for the five exams." +
               " For each of the "); 
               
                                                     // Split to be identical to Lab 1 Document sentence layout.
               
                     System.out.println("exams the max marks could be 100.");
        
        // The grades have been established for this problem utilizing a literal value.
        // Below I have assigned the grades sum via exam number.
        
                System.out.println("How many marks did you score in the first exam: " + exam1);
                System.out.println("How many marks did you score in the second exam: " +exam2);
                System.out.println("How many marks did you score in the third exam: " + exam3);
                System.out.println("How many marks did you score in the forth exam: " + exam4);
                System.out.println("How many marks did you score in the fifth exam: " + exam5);
                
                // Output should be 5 different scores depending on the exam scores added.
                // We will now capture the total of all scores to retrieve the average. 
                
                        System.out.println("The total of your marks: " + SumOfExamScores);
                        System.out.println("The total percentage of your marks: " + PercentageOfExamScores);    
                        
                    // Determine the Letter Grade by the percentage of correct answers.
                    
                    System.out.println("You got an " + letter);
        
        }
    }
