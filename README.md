# for-loop-basic-question
Find the highest number in a list using for loop.

# challenge: find maximum score from the list 'students_score'
student_scores = [150, 100, 185, 67, 290, 210, 89, 90, 120, 110, 29, 78, 65]

max_score = 0

for score in student_scores:

  if score > max_score:
  
    max_score = score

print(max_score)
