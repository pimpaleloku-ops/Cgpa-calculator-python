# Cgpa-calculator-python 
A simple CGPA CALCULATOR using python 

# CGPA Calculator for Diploma Students
print("--- Pimpri CGPA Calculator ---")
sub1 = float(input("Subject 1 marks (out of 100): "))
sub2 = float(input("Subject 2 marks: "))
sub3 = float(input("Subject 3 marks: "))
sub4 = float(input("Subject 4 marks: "))
sub5 = float(input("Subject 5 marks: "))

total = sub1 + sub2 + sub3 + sub4 + sub5
percentage = total / 5
cgpa = percentage / 9.5

print(f"\nTotal: {total}/500")
print(f"Percentage: {percentage:.2f}%")
print(f"Your CGPA: {cgpa:.2f}")
print("Made by Lokita from Pimpri!")