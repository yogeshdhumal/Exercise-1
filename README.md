# Exercise-1
#length
l = 30
#Breadth
b = 20
# height
h = 15

# volume of cuboid
def volume_of_Cuboid( l , h , b ):
    return (l * h * b)

# Biggest face surface area of cuboid
def Biggest_Surface_Area(l, b, h):
    if b >= h:
        return l*b
    else:
        return l*h
     
print("Volume in cm^3 :" , volume_of_Cuboid(l, h, b))
print("Biggest Surface Area in cm^2 =", Biggest_Surface_Area(l, h, b))
