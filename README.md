# Checker-Paws-OG

![image](https://github.com/user-attachments/assets/3392c3d1-583d-496f-baf2-00b0ac41ceb3)

## Private Key
Simpan private key di privkey.txt
untuk multi bisa dengan menaruh privatekey tiap barisnya

## Install Dependencies
```
npm i
```

## Run Checker
```
node index.js
```

## ERROR
![image](https://github.com/user-attachments/assets/e03fbc1f-21bb-4d69-8f50-4d70bd7563d6)

Kalau error kaya gitu, edit script cara kata kunci `bs58.default.decode` dan `bs58.default.encode`
hapus default contoh : `bs58.decode` dan `bs58.encode`
