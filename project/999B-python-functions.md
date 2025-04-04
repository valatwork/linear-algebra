```python
# Check if imaginary parts are negligible
print("Eigenvalues imaginary part magnitude:", torch.abs(eigenvalues.imag).max().item())
print("Eigenvectors imaginary part magnitude:", torch.abs(eigenvectors.imag).max().item())

# Convert to real if imaginary parts are small
if torch.abs(eigenvalues.imag).max() < 1e-6 and torch.abs(eigenvectors.imag).max() < 1e-6:
    eigenvalues_real = eigenvalues.real
    eigenvectors_real = eigenvectors.real
    print("\nReal eigenvalues:", eigenvalues_real)
    print("Real eigenvectors:\n", eigenvectors_real)
else:
    print("\nWarning: Some values have significant imaginary components")
 ```