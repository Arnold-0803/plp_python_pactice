employee_salary = float(input("ENTER YOUR SALRY.\n"))
employee_year_of_service = int(input("ENTER YEARS OF SERVICE.\n"))
if employee_year_of_service >= 5:
    print("CONGRATULATION YOU'VE EARNED YOURSELF A BONUS")
    net_bonus = (0.05 * employee_salary)
else:
    print("NOT ELIGIBLE FOR BONUS")
print("YOUR NET BONUS IS ksh " + str(net_bonus))
print(type(employee_year_of_service))
