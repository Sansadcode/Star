#list
# Step 1: Create an empty list
beatles = []

# Step 2: Add initial members using append()
beatles.append("John Lennon")
beatles.append("Paul McCartney")
beatles.append("George Harrison")

# Step 3: Use a loop to add new members
for member in ["Stu Sutcliffe", "Pete Best"]:
    beatles.append(input(f"Add {member}: ") or member)  # Default to member name if input is empty

# Step 4: Remove Stu Sutcliffe and Pete Best
del beatles[-2:]  # Removes the last two elements

# Step 5: Insert Ringo Starr at the beginning
beatles.insert(0, "Ringo Starr")

# Print final list
print("Final Beatles lineup:", beatles)
