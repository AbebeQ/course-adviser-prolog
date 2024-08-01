#Course Advisor

##Description
The Course Advisor is an expert course advisor system written in Prolog. It helps prospective students determine a preferable course based on their interests and grades. The system evaluates the student's grades and compares them against the specific requirements for each course to provide recommendations.

##Features
- Grade Confirmation: The system prompts the user to confirm their grades for accurate evaluation.
- Threshold Checking: The system checks if the student's grades meet the required thresholds for each course.
- Course Recommendations: The system provides recommendations on which courses the student should take based on their grades and the specific requirements for each course.

##Usage
To use the Course Advisor system, follow these steps:

1. Open the Prolog file kb.pl in a Prolog interpreter or editor that supports Prolog.
2. Load the file into the Prolog interpreter using the consult/1 predicate. For example:
3. Once the file is loaded, you can start using the system.
4. To check if a student can take a specific course, use the can_take/1 predicate. Replace CourseName with the name of the course you are interested in. For example:
The system will evaluate the query and return true if the student meets the requirements for the course, or false otherwise.
5. To get recommendations on which courses the student should take, use the should_take(X) predicate. Replace X with a variable. For example:
The system will evaluate the query and provide a response with the value of X that satisfies the conditions for a course or field of study that the student should take. The response will be in the form of a list of courses or fields.
6. Repeat steps 4 and 5 to check other courses or get different recommendations.

Example
Suppose you want to check if a student can take the course "statistics". You can use the following query:
The system will evaluate the query and return true if the student meets the requirements for the "statistics" course, or false otherwise.

To get recommendations on which courses the student should take, you can use the following query:
The system will evaluate the query and provide a response with the value of X that satisfies the conditions for a course or field of study that the student should take.

Remember to provide the necessary input when prompted by the system, such as confirming grades and specifying threshold values.

Conclusion
The Course Advisor system provides a convenient way for prospective students to determine a preferable course based on their interests and grades. By following the usage instructions and providing the necessary input, users can easily check if they meet the requirements for specific courses and get recommendations on which courses they should take. 
