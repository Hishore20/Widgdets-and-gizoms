# Widgdets-and-gizoms



An online retailer sells two products: widgets and gizmos. Each widget weighs 75 grams. Each gizmo weighs 112 grams.

Write a program that reads the number of widgets and the number of gizmos in an order from the user. Then your program
should compute and display the total weight of the order

Declare Widgest and gizmos as:

wid=75
giz=112
Logic Test Case 1

Input (stdin)
28

22

Expected Output

4.564
Logic Test Case 2

Input (stdin)
86

47

Expected Output

11.714







a=int(input())
b=int(input())
c=75*a
d=112*b
w=(c+d)/1000
print('%.3f'%w)
