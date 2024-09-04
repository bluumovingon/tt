import matplotlib.pyplot as plt

def get_input(prompt):
    # Menggunakan eval untuk mengeksekusi input sebagai ekspresi Python
    return eval(input(prompt))

# Mendapatkan nilai x dan y dari pengguna
x = get_input("Masukkan nilai x (misalnya: [1, 2, 3]): ")
y = get_input("Masukkan nilai y (misalnya: [4, 5, 6]): ")

# Memastikan x dan y adalah list atau array yang sesuai
plt.plot(x, y, label='Line plot')  # Menggambar garis
plt.scatter(x, y, color='red', label='Scatter plot')  # Menggambar titik
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Plot dan Scatter')
plt.legend()
plt.show()
