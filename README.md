# Task1
def show_menu(): 
    print("    \n            OUR MENU\n")
    print("Starters:")
    print("1. Chicken Wings - Rs. 300")
    print("2. Fries - Rs. 150")
    print("3. Soup - Rs. 200")
    print("Main Course:")
    print("4. Biryani - Rs. 250")
    print("5. Chicken Karahi - Rs. 800")
    print("6. Naan - Rs. 30")
    print("7. BBQ Platter - Rs. 1200")
    print("Desserts:")
    print("8. Kheer - Rs. 120")
    print("9. Gulab Jamun - Rs. 100")
    print("10. Ice Cream - Rs. 150")
    print("Beverages:")
    print("11. Soft Drink - Rs. 50")
    print("12. Lassi - Rs. 100")
    print("13. Tea - Rs. 40")
    print("14. Coffee - Rs. 70")
while True:
    print("Welcome to Restaurant management system")
    print("    1. View Menu")
    print("    2. Exit")
    choice = input("Choose an option (1 or 2): ")
    if choice=='1':
        show_menu()
    elif choice=='2':
        print("Thankyou For visisting! Goodbye!")
        break
    else:
        print("\nInvalid option. Please try again.\n")

