# Ritcher-scale
ritcher=float(input("Please enter ritcher scale"))

if ritcher>= 8.0:
    print("most structures fall")
elif ritcher>= 7.0:
    print("many buildings destroyed")
elif ritcher>= 6.0:
    print("many buildings considerably damaged, some collapse")
elif ritcher>= 4.5:
    print("damage to poorly constructed buildings")
else:
    print("no destruction of buildings")
