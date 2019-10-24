tanggal = int(input("Masukkan Tanggal(angka)>"))
bulan = int(input("Masukkan Bulan(angka)>"))
if (tanggal >= 21 and bulan == 3) or (tanggal <= 19 and bulan == 4):
    print('Zodiak Aries')
elif (tanggal >= 20 and bulan == 4) or (tanggal <= 20 and bulan == 5):
    print('Zodiak Taurus')
elif (tanggal >= 21 and bulan == 5) or (tanggal <= 20 and bulan == 6):
    print('Zodiak Gemini')
elif (tanggal >= 21 and bulan == 6) or (tanggal <= 22 and bulan == 7):
    print('Zodiak Cancer')
elif (tanggal >= 23 and bulan == 7) or (tanggal <= 22 and bulan == 8):
    print('Zodiak Leo')
elif (tanggal >= 23 and bulan == 8) or (tanggal <= 22 and bulan == 9):
    print('Zodiak Virgo')
elif (tanggal >= 23 and bulan == 9) or (tanggal <= 22 and bulan == 10):
    print('Zodiak Libra')
elif (tanggal >= 23 and bulan == 10) or (tanggal <= 21 and bulan == 11):
    print('Zodiak Scorpio')
elif (tanggal >= 22 and bulan == 11) or (tanggal <= 21 and bulan == 12):
    print('Zodiak Sagitarius')
elif (tanggal >= 22 and bulan == 12) or (tanggal <= 19 and bulan == 1):
    print('Zodiak Capricorn')
elif (tanggal >= 20 and bulan == 1) or (tanggal <= 18 and bulan == 2):
    print('Zodiak Aquarius')
else:
    print("Tanggal atau bulan salah!")
