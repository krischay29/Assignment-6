# Assignment-6
# Create matrix A
A <- matrix(c(2, 0, 1, 3), ncol = 2)


# Create matrix B
B <- matrix(c(5, 2, 4, -1), ncol = 2)


# Find A + B
AddingAB <- A + B


# Find A - B
SubtractAB <- A - B


# Create a diagonal matrix with values 4, 1, 2, 3
diagMatrix <- diag(c(4, 1, 2, 3), ncol = 4)



# Generate the specified genMatrix

genMatrix <- diag(c(3, 3, 3, 3, 3), ncol = 5)

genMatrix[1, ] <- c(3, 1, 1, 1, 1)

genMatrix[, 1] <- c(3, 2, 2, 2, 2)



# Print matrices

print("Matrix A:")

print(A)

print("Matrix B:")

print(B)

print("A + B:")

print(AddingAB)

print("A - B:")

print(SubtractAB)

print("Diagonal matrix:")

print(diagMatrix)

print("Generated matrix:")

print(genMatrix)
