# Testing
A usage of GitHub
##
# this is a testing python
#
sum = ((10 + 2) * 100 / 5 - 200)
print(id(sum))
print(type(sum))

# Using functions in an expression
power = pow(2, 10)
print(id(power))
power2 = power
print(id(power2))

# Using eval in an expression
adding = eval( "2.5+2.5" )
print(adding)

# string print and manipulation
string1 = "this is the first testing message"
print (string1) # this is the print out the string

string2 = "what is up"
string3 = string1 + string2
print(string3)

#  += feature
my_tuple = [10, 20, 30]
my_tuple += [40,50]
print ("my typle is ",my_tuple)

list_vowels = ['a','e','i']
list_vowels += ['o','u']
print("my list vowels are: ",list_vowels)

# Multliple line
list_vowels2 = ['a',
'e',\
'i']
list_vowels2 += ['o','u']
print("my list vowels 2 are: ",list_vowels2)

# implicit line continuation
newpower = pow(2,
10)
print("new power: ",newpower)


# python indentication
def demo_function(num):
    print("This is demo function")
    if num % 2 == 0:   # modulus remainder
        print("even number")
        return True
    else:
        print("odd number")
        return False

num = 9
if demo_function(num) is True:
    print(num, "is a Even number","\nfor sure")
else:
    print(num, "is a Odd number","\nfor sure")
~                                                                                                     
~                                
