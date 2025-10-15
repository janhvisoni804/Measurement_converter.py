print("select 1 for inch to foot conversion")
print("select 2 for inch to yard conversion")
print("select 3 for inch to centimetre conversion")
print("select 4 for inch to meter conversion")
print("\n")
choice = int(input("enter choice "))
if choice == 1:
    measure = float(input("enter measurement in inches "))
    foot = measure / 12
    print("measurement in foot is", foot)
elif choice == 2:
    measure = float(input("enter measurement in inches "))
    yard = measure / 36
    print("measurement in yard is", yard)
elif choice == 3:
    measure = float(input("enter measurement in inches "))
    centimetre = measure * 2.54
    print("measurement in centimetre is", centimetre)
elif choice == 4:
    measure = float(input("enter measurement in inches "))
    meter = measure / 39.37
    print("measurement in meter is", meter)
else:
    print("invalid choice")
