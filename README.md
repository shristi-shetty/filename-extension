# filename-extension
def extension(z):
    if   (z=='py'):
          return"python";

    elif (z=='java'):
          return"java";

    elif (z=='c'):
          return"c";

    else:
          return"none";


x=input("Input a filename: ")
y=x.split(".")
z=y[-1]
print("The extension of the file is: "+ str(extension(z)))
