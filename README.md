# Plp-Python-week-2
my_list = []
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)
print("Appended numbers:", my_list)
my_list.insert(1, 15)
print("Insertion of 15 to index 1", my_list)
your_list = [50, 60, 70]
my_list.extend(your_list)
print("insertsion of 50, 60, 70 to my_list", my_list)
my_list.remove(70)
print("Removal of 70", my_list)
sort = sorted(my_list)
print("Arrangement in ascending order:", sort)
index = sort.index(30)
print("index of 30 is:", index)
