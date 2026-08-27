# miniExercisePy

def calculate_average(scores):

    average= sum(scores)/len(scores)

    return average

def get_letter_grade(average):
    if average >=90:
        return "A"
    elif average>=80:
        return "B"
    elif  average>=70:
        return "C"
    else:
        return "F"

student_scores=[]

for item in range(1,4):
    student_scores.append(float(input(" please enter your score ")))
result=calculate_average(student_scores)
print(f"average score : {result}")

grade=get_letter_grade(result)
print(f" your final grade is {grade}")
    
