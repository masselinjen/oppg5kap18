# oppg5kap18
type = (input("Fahrenheit eller celsius?:"))
antall_grader = float(input("Skriv inn antall grader:"))

if type == "celsius":
    fahrenheit = (antall_grader*1.8)+32   
    print(f"{fahrenheit} fahrenheit.")
