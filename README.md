# 6-19
True Or False Matrix Mult
def matrix_mult(mat1,mat2):
  if len(mat1[0])==len(mat2):
    return True
  else:
    return False
  

mat1=[[1,2,3],[4,5,6]]
mat2=[[7,8,9],[1,3,5]]

print (matrix_mult(mat1,mat2))

