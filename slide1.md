---
marp: true
theme: gaia
footer: "**2023-B-07-a**"
paginate: true 
---
問題１
位相回転するゲートは？
- Xゲート
- Yゲート
- Zゲート
- Tゲート
- Sゲート
---

---
問題２
ビット反転するゲートは？
- Xゲート
- Yゲート
- Zゲート
- Tゲート
- Sゲート

---
問題３
下記を実行すると、量子状態はどうなりますか？

![100%](./image/3.png)

---
問題４
下記を実行すると、量子状態はどうなりますか？

![100%](./image/4.png)

---
問題５
下記と等価なゲートは？

![100%](./image/5.png)

---
問題６
下記と等価なゲートは？

![100%](./image/6.png)

---
問題７
Sゲートのフェーズの値は？
- π/2
- π/4
- π/8
- π

---
問題８
Tゲートのフェーズの値は？
- π/2
- π/4
- π/8
- π

---
問題９
QuantumCircuit　正しくない記述は？
- QuantumCircuit(QuantumRegister(4))
- QuantumCircuit(QuantumRegister(4), ClassicalRegister(3))
- QuantumCircuit(QuantumRegister(4, 'qr0'), QuantumRegister(2, 'qr1'))
- QuantumCircuit（4,4)
- QuantumCircuit（cr,qr)
- qr = QuantumRegister(2)
  cr = ClassicalRegister(2)
  qc = QuantumCircuit(cr[0:2],qr[0:2])

---
問題10 Measure　正しくない記述は？
- circuit = QuantumCircuit(2, 2)
  circuit.measure([0,1], [0,1])
- circuit = QuantumCircuit(2, 2)
  circuit.measure(0, 0)
  circuit.measure(1, 1)
- qreg = QuantumRegister(2, "qreg")
  creg = ClassicalRegister(2, "creg")
  circuit = QuantumCircuit(qreg, creg)
  circuit.measure(qreg, creg)
- circuit = QuantumCircuit(qreg, creg)
  circuit.measure(qreg[0], creg[0])
  circuit.measure(qreg[1], creg[1])
---
問題10 Measure　正しくない記述は？
