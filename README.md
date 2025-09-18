# Demoo
For Numpy 
# a=np.array(40)      #0 dimension
# b=np.array([1,2,3,4,5,6,7,8])       #1 dimension
# c=np.array([[1,2,3],[3,2,1]])         #2 dimension
# d=np.array([[[1,2,3],[4,5,6]],[[7,8,9],[1,2,3]]])


# print(a.ndim)
# print(b.ndim)
# print(c.ndim)
# print(d.ndim)

# arr = np.array([[[1, 2], [3, 4]], [[5, 6], [7, 8]]])
# print(arr[0, 1,0])

# arr=np.array([1,2,3,4])
# arr[0]


# d=np.array([[[1,2,3],[4,5,6]],[[7,8,9],[1,2,3]]])
# print(d[0,1,2])     #6
# print(d[1,0,2])     #9

# print(d[1,0,2]+d[1,1,0])
# print(d[1,0,2]+d[1,1,-1])

# arr = np.array([[[1, 2, 3], [4, 5, 6]], [[7, 8, 9], [10, 11, 12]]])

# print(arr[0, 1, -1])

# arr=np.array([
#     [1, 2, 3],
#     [4, 5, 6],
#     [7, 8, 9]
# ])
# arr
# print(arr[1,-1])
# print(arr[0])
# print(arr[1])
# print(arr[2,-1])
# print(arr[0:2, 0:2])
# cross= [arr[0,0], arr[1,1], arr[2,2]]
# print(cross)
# cross=arr.diagonal()
# print(cross)
# cross1=[arr[0,2], arr[1,1], arr[2,0]]
# print(cross1)
# slic1=[arr[2, 0:4], arr[1, 0:4], arr[0 ,0:4]]
# print(slic1)
# slic=[arr[0, ::-1], arr[1, ::-1], arr[2, ::-1]]
# print(slic)
# flat=arr.flatten()
# print(flat)
# print(flat[::2]) 

# arr = np.array([
#     [ 1,  2,  3,  4],
#     [ 5,  6,  7,  8],
#     [ 9, 10, 11, 12],
#     [13, 14, 15, 16]
# ])
# print(arr[2,1])
# print(arr[3, 0:4])
# lastcolun=[arr[0,3], arr[1,3],arr[2,3],arr[3,3]]
# print(lastcolun)
# diagonal=arr.diagonal()
# print(diagonal)
# antidiagonal=[arr[0,3], arr[1,2], arr[2,1], arr[3,0]]
# print(antidiagonal)
# raw=[arr[1, 1:3], arr[2, 1:3]]
# print(raw)
# vertically=[arr[3, 0:4], arr[2, 0:4], arr[1, 0:4], arr[0, 0:4]]
# print(vertically)
# horizent=[arr[0, ::-1], arr[1, ::-1], arr[2, ::-1], arr[3, ::-1]]
# print(horizent)
# flat=arr.flatten()
# print(flat)
# flat1=flat[::2]
# print(flat1)
# jump=[arr[0, :3:2], arr[2, :3:2]]
# print(jump)

