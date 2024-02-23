# Extraction The LAST Digit

-> If we need to extract th last digit of any number, just Mod this number with 10

Suppose we have 123, we need 3..mod this number with 10. 123 % 10. The the reminder should be 3. THen again mod with 10. Now we will found 2.

Python:

x = 1234;

while(x>0):
    store = x % 10;
    print(store)

    x = x // 10;

# Reverse a number

-> Suppouse You get a number 10400, You have to reverse it, But instead of having 00401, you have to find 401

Python:

x = 10400;
n = 0
while(x>0):
    
    store = x % 10;

    n= (n*10)+store
    
    x = x // 10;
print(n)
