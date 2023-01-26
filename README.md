# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
    open the required file by using the function "with" in read mode
   
### Step 2:
    open the another requried file by using the function "with" in append mode to append
    
    
### Step 3: 
     use for loop in file 1
   
### Step 4:  
      use write function
   
### Step 5: 
      to write the file 1 contect in file 2
### Step 6: 
    end the program

## PROGRAM:
~~~
  # Developed by: panimalar.p
   #RegisterNumber:  22009107
   
   with open('f1.txt','r') as firstfile:
       with open('f2.txt','a') as secondfile:
           for line in firstfine:
               secondfile.write(line)
~~~
### OUTPUT:

![Screenshot (222)](https://user-images.githubusercontent.com/121490826/214883509-743a9593-aedb-4ab6-ac6b-f5351a79a4b1.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file
