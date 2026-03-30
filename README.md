# python-set-operations
“A Python program demonstrating set operations like union, intersection, difference, and symmetric difference.”
# Define two sets
E = {0, 2, 4, 6, 8}
N = {0, 1, 2, 3, 4, 5}

# Union
union_result = E.union(N)

# Intersection
intersection_result = E.intersection(N)

# Difference (E - N)
difference_result = E.difference(N)

# Symmetric Difference
symmetric_difference_result = E.symmetric_difference(N)

# Display results
print("Set E:", E)
print("Set N:", N)

print("\nUnion of E and N is:", union_result)
print("Intersection of E and N is:", intersection_result)
print("Difference of E and N is:", difference_result)
print("Symmetric difference of E and N is:", symmetric_difference_result)
