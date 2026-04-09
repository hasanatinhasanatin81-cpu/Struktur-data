# Struktur-data
nama_array = list("hasanatin")
key = 'a'

def search_array(data, target):
    for i in range(len(data)):
        if data[i] == target:
            return i  # Mengembalikan index pertama yang ditemukan
    return -1

# Eksekusi
index = search_array(nama_array, key)
print(f"Array: Huruf '{key}' pertama ditemukan pada index
