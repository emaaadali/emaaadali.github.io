import tkinter as tk

root = tk.Tk()
root.title("User Information")

label_full_name = tk.Label(root, text="Full Name")
label_full_name.grid(row=0, column=0)

label_country = tk.Label(root, text="Country")
label_country.grid(row=1, column=0)

label_age = tk.Label(root, text="Age")
label_age.grid(row=2, column=0)

entry_full_name = tk.Entry(root)
entry_full_name.grid(row=0, column=1)

entry_country = tk.Entry(root)
entry_country.grid(row=1, column=1)

entry_age = tk.Entry(root)
entry_age.grid(row=2, column=1)

def submit_info():
    full_name = entry_full_name.get()
    country = entry_country.get()
    age = entry_age.get()
    print(f"Name: {full_name}, Country: {country}, Age: {age}")

submit_button = tk.Button(root, text="Submit", command=submit_info)
submit_button.grid(row=3, column=0, columnspan=2)

root.mainloop()



