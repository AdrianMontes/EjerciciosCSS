# **flex-direction**
# Nivel 1
![Error](resources/FlexboxZombie_1_1.png)

---
# Nivel 2
![Error](resources/FlexboxZombie_1_2.png)

---
# Nivel 3
![Error](resources/FlexboxZombie_1_3.png)

---
# Nivel 4
![Error](resources/FlexboxZombie_1_4.png)

---
---
# **justify-content**
# Nivel 1
![Error](resources/FlexboxZombie_2_1.png)

---
# Nivel 2
![Error](resources/FlexboxZombie_2_2.png)

---
# Nivel 3
![Error](resources/FlexboxZombie_2_3.png)

---
# Nivel 4
![Error](resources/FlexboxZombie_2_4.png)

---
# Nivel 5
![Error](resources/FlexboxZombie_2_5.png)

---
# Nivel 6
![Error](resources/FlexboxZombie_2_6.png)

---
# Nivel 7
![Error](resources/FlexboxZombie_2_7.png)

---
# Nivel 8
![Error](resources/FlexboxZombie_2_8.png)

---
# Nivel 9
![Error](resources/FlexboxZombie_2_9.png)

---
# Nivel 10
![Error](resources/FlexboxZombie_2_10.png)

---
# Nivel 11
![Error](resources/FlexboxZombie_2_11.png)

---
# Nivel 12
![Error](resources/FlexboxZombie_2_12.png)

---
# Nivel 13
![Error](resources/FlexboxZombie_2_13.png)

---
# Nivel 14
![Error](resources/FlexboxZombie_2_14.png)

---
# Nivel 15
![Error](resources/FlexboxZombie_2_15.png)

---
# Nivel 16
![Error](resources/FlexboxZombie_2_16.png)

---
---
# **align-items**
# Nivel 1
![Error](resources/FlexboxZombie_3_1.png)

---
# Nivel 2
![Error](resources/FlexboxZombie_3_2.png)

---
# Nivel 3
![Error](resources/FlexboxZombie_3_3.png)

---
# Nivel 4
![Error](resources/FlexboxZombie_3_4.png)

---
# Nivel 5
![Error](resources/FlexboxZombie_3_5.png)

---
# Nivel 6
![Error](resources/FlexboxZombie_3_6.png)

---
# Nivel 7
![Error](resources/FlexboxZombie_3_7.png)

---
# Nivel 8
![Error](resources/FlexboxZombie_3_8.png)

---
# Nivel 9
![Error](resources/FlexboxZombie_3_9.png)

---
# Nivel 10
![Error](resources/FlexboxZombie_3_10.png)

---
# Nivel 11
![Error](resources/FlexboxZombie_3_11.png)

---
# Nivel 12
![Error](resources/FlexboxZombie_3_12.png)

---
# Nivel 13
![Error](resources/FlexboxZombie_3_13.png)

---
# Nivel 14
![Error](resources/FlexboxZombie_3_14.png)

---
# Nivel 15
![Error](resources/FlexboxZombie_3_15.png)

---
# Nivel 16
![Error](resources/FlexboxZombie_3_16.png)

---
# Nivel 17
![Error](resources/FlexboxZombie_3_17.png)

---
---
# **align-self**
# Nivel 1
![Error](resources/FlexboxZombie_4_1.png)

---
# Nivel 2
![Error](resources/FlexboxZombie_4_2.png)

---
# Nivel 3
![Error](resources/FlexboxZombie_4_3.png)

---
# Nivel 4
![Error](resources/FlexboxZombie_4_4.png)

---
# Nivel 5
![Error](resources/FlexboxZombie_4_5.png)

---
# Nivel 6
![Error](resources/FlexboxZombie_4_6.png)

---
# Nivel 7
![Error](resources/FlexboxZombie_4_7.png)

---
# Nivel 8
![Error](resources/FlexboxZombie_4_8.png)

---
# Nivel 9
![Error](resources/FlexboxZombie_4_9.png)

---
# Nivel 10
![Error](resources/FlexboxZombie_4_10.png)

---
# Nivel 11
![Error](resources/FlexboxZombie_4_11.png)

---
# Nivel 12
![Error](resources/FlexboxZombie_4_12.png)

---
# Nivel 13
![Error](resources/FlexboxZombie_4_13.png)

---
# Nivel 14
![Error](resources/FlexboxZombie_4_14.png)

---
---
# **flex-grow**
# Nivel 1
![Error](resources/FlexboxZombie_5_1.png)

---
# Nivel 2
![Error](resources/FlexboxZombie_5_2.png)

---
# Nivel 3
![Error](resources/FlexboxZombie_5_3.png)

---
# Nivel 4
![Error](resources/FlexboxZombie_5_4.png)

---
# Nivel 5
![Error](resources/FlexboxZombie_5_5.png)

---
# Nivel 6
![Error](resources/FlexboxZombie_5_6.png)

---
# Nivel 7
![Error](resources/FlexboxZombie_5_7.png)

---
# Nivel 8
![Error](resources/FlexboxZombie_5_8.png)

---
# Nivel 9
![Error](resources/FlexboxZombie_5_9.png)

crossbow {
  display: flex;
  flex-direction: row-reverse;
  justify-content: space-around;
  align-items: center;
}

.target.goo {
  align-self: center;
  align-items: center;
  flex-grow: 1;
}

.target:nth-of-type(1) {
  align-self: flex-end;
  flex-grow: 2;
}

---
# Nivel 10
![Error](resources/FlexboxZombie_5_10.png)

---
# Nivel 11
![Error](resources/FlexboxZombie_5_11.png)

---
# Nivel 12
![Error](resources/FlexboxZombie_5_12.png)

crossbow {
  display: flex;
  flex-direction: row-reverse;
  justify-content: space-between;
  align-items: flex-start;
}

.target.goo {
  flex-grow: 1;
}

.target:nth-of-type(1) {
  flex-grow: 0;
}

.target:nth-of-type(4) {
  flex-grow: 3;
}

---
# Nivel 13
![Error](resources/FlexboxZombie_5_13.png)

crossbow {
  display: flex;
  flex-direction: column-reverse;
}

.target.goo {
  align-self: center;
  flex-grow: 1;
}

.target:nth-of-type(2) {
  align-self: stretch;
  flex-grow: 1;
}

.target:nth-of-type(3) {
  flex-grow: 0;
}

---
# Nivel 14
![Error](resources/FlexboxZombie_5_14.png)

crossbow {
  display: flex;
  align-items: flex-end;
}

.target.goo {
 align-self: flex-start;
 flex-grow: 1;
}

.target:nth-of-type(3) {
  align-self: stretch;
}

---
# Nivel 15
![Error](resources/FlexboxZombie_5_15.png)

crossbow {
  display: flex;
  flex-direction: row-reverse;
  justify-content: space-between;
  align-items: flex-end;
}

.target.goo {
  flex-grow: 1;
}

.target:nth-of-type(4) {
  flex-grow: 3;
}

---
# Nivel 16
![Error](resources/FlexboxZombie_5_16.png)

---
---
