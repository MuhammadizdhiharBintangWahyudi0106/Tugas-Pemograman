import datetime
nama = input("Nama kamu siapa? ")
tahun_lahir = int(input("Tahun lahir kamu? "))
tahun_sekarang = datetime.datetime.now().year
umur = tahun_sekarang - tahun_lahir
print(f"Halo {nama}, umur kamu sekarang adalah {umur} tahun.")
