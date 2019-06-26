nim = []
nama = []
jurusan = []
alamat = []


pilihan = 1
while pilihan != 0 :
    print ("1. Masukan Data.")
    print ("2. tampilkan data.")
    print ("3. hapus data.")
    print ("0. exit.")

    pilihan = int(input("masukan pilihan anda : "))
    print('')
    print('')
    print('')
    print('')
    if pilihan == 1 :
        masnim = input("masukan nim : ")
        nim.append({'nim' : masnim})
        masnama = input("masukan nama : ")
        nama.append({'nama' : masnama})
        masjurusan = input("masukan jurusan : ")
        jurusan.append({'jurusan' : masjurusan})
        masalamat = input ("masukan alamat : ")
        alamat.append({'alamat' : masalamat})
        
    elif pilihan == 2 :
        penentu = True
        for i in range (len(nim)) :
            if penentu :
                print ("nim\t       nama\t  jurusan\t      alamat")
            print (nim[i]['nim'],'\t',nama[i]['nama'],'\t',jurusan[i]['jurusan'],'\t',alamat[i]['alamat'])
            penentu = False
            
    elif pilihan == 3 :
        masnim = input("masukan nim : ")
        for i in range (len(nim)) :
            if masnim == nim[i]['nim'] :
                print (i)
                del nim[i]
                del nama[i]
                del jurusan[i]
                del alamat[i]
                break
    print('')
    print('')
    print('')
    print('')
