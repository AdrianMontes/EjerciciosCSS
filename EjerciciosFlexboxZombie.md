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
# **flex-shrink**
# Nivel 1
![Error](resources/FlexboxZombie_6_1.png)

---
# Nivel 2
![Error](resources/FlexboxZombie_6_2.png)

---
# Nivel 3
![Error](resources/FlexboxZombie_6_3.png)

---
# Nivel 4
![Error](resources/FlexboxZombie_6_4.png)

---
# Nivel 5
![Error](resources/FlexboxZombie_6_5.png)

---
# Nivel 6
![Error](resources/FlexboxZombie_6_6.png)

---
# Nivel 7
![Error](resources/FlexboxZombie_6_7.png)

crossbow {
  display: flex;
  justify-content: space-between;
}

.target.goo {
  align-self: flex-start;
  flex-grow: 1;
}

.target.male {
  align-self: center;
}

---
# Nivel 8
![Error](resources/FlexboxZombie_6_8.png)

crossbow {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.target:nth-of-type(2) {
  align-self: stretch;
}

.target:nth-of-type(3) {
  flex-grow: 1;
  flex-shrink: 0;
}

---
# Nivel 9
![Error](resources/FlexboxZombie_6_9.png)

crossbow {
  display: flex;
  flex-direction: row-reverse;
  justify-content: space-around;
  align-items: flex-start;
}

.target:nth-of-type(1) {
  align-self: center;
}

.target:nth-of-type(2) {
  align-self: center;
  flex-grow: 1;
  flex-shrink: 0;
}

---
# Nivel 10
![Error](resources/FlexboxZombie_6_10.png)

---
# Nivel 11
![Error](resources/FlexboxZombie_6_11.png)

crossbow {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
}

.target:nth-of-type(2) {
  flex-grow: 2;
  flex-shrink: 1;
}

.target:nth-of-type(3) {
  align-self: stretch;
  flex-grow: 1;
  flex-shrink: 2;
}

---
# Nivel 12
![Error](resources/FlexboxZombie_6_12.png)

crossbow {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.target:nth-of-type(1) {
  flex-shrink: 2;
}

.target:nth-of-type(2) {
  flex-grow: 1;
  flex-shrink: 0;
}

---
# Nivel 13
![Error](resources/FlexboxZombie_6_13.png)

crossbow {
  display: flex;
  flex-direction: column-reverse;
}

.target.goo {
  
}

.target:nth-of-type(1) {
  align-self: flex-end;
  flex-grow: 1;
}

.target:nth-of-type(2) {
  flex-grow: 1;
  flex-shrink: 2;
}

.target:nth-of-type(3) {
  align-self: flex-start;
  flex-grow: 2;
  flex-shrink: ;
}

# Nivel 14
![Error](resources/FlexboxZombie_6_14.png)

crossbow {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
}

.target.goo {
  align-self: flex-start;
  flex-grow: 1;
}

.target:nth-of-type(1) {
  flex-shrink: 0;
  flex-grow: 3;
}

---
# Nivel 15
![Error](resources/FlexboxZombie_6_15.png)

crossbow {
  display: flex;
  flex-direction: row-reverse;
  justify-content: space-between;
  align-items: flex-end;
}

.target:nth-of-type(2) {
  align-self: stretch;
  flex-grow: 2;
  flex-shrink: 2;
}

.target:nth-of-type(3) {
  align-self: flex-start;
  flex-grow: 1;
  flex-shrink: 0;
}

---
# Nivel 16
![Error](resources/FlexboxZombie_6_16.png)

crossbow {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
}

.target:nth-of-type(1) {
  align-self: stretch;
  flex-shrink: 0;
}

.target:nth-of-type(2) {
  align-self: stretch;
  flex-grow: 1;
}

---
---
# **flex-basis**
# Nivel 1
![Error](resources/FlexboxZombie_7_1.png)

---
# Nivel 2
![Error](resources/FlexboxZombie_7_2.png)

---
# Nivel 3
![Error](resources/FlexboxZombie_7_3.png)

---
# Nivel 4
![Error](resources/FlexboxZombie_7_4.png)

---
# Nivel 5
![Error](resources/FlexboxZombie_7_5.png)

---
# Nivel 6
![Error](resources/FlexboxZombie_7_6.png)

---
# Nivel 7
![Error](resources/FlexboxZombie_7_7.png)

---
# Nivel 8
![Error](resources/FlexboxZombie_7_8.png)

---
# Nivel 9
![Error](resources/FlexboxZombie_7_9.png)

---
# Nivel 10
![Error](resources/FlexboxZombie_7_10.png)

---
# Nivel 11
![Error](resources/FlexboxZombie_7_11.png)

---
# Nivel 12
![Error](resources/FlexboxZombie_7_12.png)

---
# Nivel 13
![Error](resources/FlexboxZombie_7_13.png)

---
# Nivel 14
![Error](resources/FlexboxZombie_7_14.png)

crossbow {
  display: flex;
  justify-content: flex-start;
  align-items: center;
}

.target.goo {
  flex-basis: 50%;
}

.target:nth-of-type(3) {
  align-self: stretch;
}

---
# Nivel 15
![Error](resources/FlexboxZombie_7_15.png)

crossbow {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
}

.target.goo {
  align-self: center;
  flex-grow: 1;
}

.target:nth-of-type(3) {
  align-self: flex-start;
  flex-grow: 0;
  flex-basis: 75px;
}

---
# Nivel 16
![Error](resources/FlexboxZombie_7_16.png)

crossbow {
  display: flex;
  flex-direction: column-reverse;
  align-items: center;
}

.target.goo {
  flex-grow: 1;
}

.target:nth-of-type(2) {
  max-width: none;
  max-height: 200px;
}

---
# Nivel 17
![Error](resources/FlexboxZombie_7_17.png)

crossbow {
  display: flex;
  justify-content: center;
  align-items: center;
}

.target.goo {
  flex-basis: 200px;
}

.target:nth-of-type(1) {
  flex-shrink: 0;
}

.target:nth-of-type(2) {
  flex-basis: 200px;
  min-width: 300px;
}

---
# Nivel 18
![Error](resources/FlexboxZombie_7_18.png)

crossbow {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: flex-start;
}

.target.goo {
  flex-basis: 250px;
}

.target:nth-of-type(1) {
  flex-shrink: 0;
}

---
# Nivel 19
![Error](resources/FlexboxZombie_7_19.png)

crossbow {
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

.target.goo {
  flex-basis: 200px;
}

.target:nth-of-type(2) {
  flex-shrink: 0;
}

---
# Nivel 20
![Error](resources/FlexboxZombie_7_20.png)

crossbow {
  display: flex;
}

.target.goo {
  flex-grow: 1;
  flex-shrink: 1;
  flex-basis: 0;
}

.target:nth-of-type(3) {
  align-self: flex-start;
}

---
---
# **order**
# Nivel 1
![Error](resources/FlexboxZombie_8_1.png)

---
# Nivel 2
![Error](resources/FlexboxZombie_8_2.png)

---
# Nivel 3
![Error](resources/FlexboxZombie_8_3.png)

---
# Nivel 4
![Error](resources/FlexboxZombie_8_4.png)

---
# Nivel 5
![Error](resources/FlexboxZombie_8_5.png)

---
# Nivel 6
![Error](resources/FlexboxZombie_8_6.png)

crossbow {
  display: flex;
  justify-content: center;
  align-items: center;
}

.target.female {
  order: 1;  
}

.target.goo {
  order: 2;
}

.target.male {
  order: 3;
}

---
# Nivel 7
![Error](resources/FlexboxZombie_8_7.png)

crossbow {
  display: flex;
  justify-content: flex-end;
  align-items: flex-start;
}

.target.goo {
  order: -1;
  align-self: stretch;
  flex-grow: 1;
}

---
# Nivel 8
![Error](resources/FlexboxZombie_8_8.png)

crossbow {
  display: flex;
  flex-direction: row-reverse;
  justify-content: center;
  align-items: flex-start;
}

.target.goo {
  order: 1;
  align-self: flex-end;
  flex-basis: 350px;
}

---
# Nivel 9
![Error](resources/FlexboxZombie_8_9.png)

---
# Nivel 10
![Error](resources/FlexboxZombie_8_10.png)

---
# Nivel 11
![Error](resources/FlexboxZombie_8_11.png)

crossbow {
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.target.female {
  order: 2;
}
  
.target.goo {
  order: 3;
}

.target.male {
  order: 1;
}

---
# Nivel 12
![Error](resources/FlexboxZombie_8_12.png)

crossbow {
  display: flex;
  align-items: center;
}

.target.goo {
  order: 2;
  flex-grow: 1;
}
  
.target.male {
  order: 1;
}

---
# Nivel 13
![Error](resources/FlexboxZombie_8_13.png)

crossbow {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
}

.target.female {
  order: -1;
}
  
.target:nth-of-type(1) {
  align-self: flex-end;
  flex-grow: 1;
  flex-shrink: 0;
}

---
---
# **flex-wrap**
# Nivel 1
![Error](resources/FlexboxZombie_9_1.png)

---
# Nivel 2
![Error](resources/FlexboxZombie_9_2.png)

---
# Nivel 3
![Error](resources/FlexboxZombie_9_3.png)

---
# Nivel 4
![Error](resources/FlexboxZombie_9_4.png)

---
# Nivel 5
![Error](resources/FlexboxZombie_9_5.png)

---
# Nivel 6
![Error](resources/FlexboxZombie_9_6.png)

---
# Nivel 7
![Error](resources/FlexboxZombie_9_7.png)

---
# Nivel 8
![Error](resources/FlexboxZombie_9_8.png)

---
# Nivel 9
![Error](resources/FlexboxZombie_9_9.png)

---
# Nivel 10
![Error](resources/FlexboxZombie_9_10.png)

---
# Nivel 11
![Error](resources/FlexboxZombie_9_11.png)

crossbow {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  flex-wrap: wrap;
  flex-basis: 50%;
}

.target.goo {
  flex-basis: 50%;
}

---
# Nivel 12
![Error](resources/FlexboxZombie_9_12.png)

---
# Nivel 13
![Error](resources/FlexboxZombie_9_13.png)

---
# Nivel 14
![Error](resources/FlexboxZombie_9_14.png)

---
# Nivel 15
![Error](resources/FlexboxZombie_9_15.png)

crossbow {
  display: flex;
  justify-content: flex-start;
  align-items: flex-start;
  flex-wrap: wrap;
}

.target:nth-of-type(2) {
  flex-grow: 1;
}

.target:nth-of-type(3) {
  flex-grow: 1;
}

---
---