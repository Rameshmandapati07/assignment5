Task 1:
student_marks = {
    "Alice": 85,
    "Bob": 90,
    "Charlie": 78
}

student_name = input("Enter the student's name: ")

if student_name in student_marks:
    print(f"{student_name}'s marks: {student_marks[student_name]}")
else:
    print("Student not found.")

Task 2:
numbers = list(range(1, 11))  
extracted = numbers[:5]       
reversed_extracted = extracted[::-1] 

print("Extracted List:", extracted)
print("Reversed List:", reversed_extracted)

