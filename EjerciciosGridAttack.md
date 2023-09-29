# **Nivel 1**
![Error](resources/GridAttack_1.png)

---
# **Nivel 2**
![Error](resources/GridAttack_2.png)

---
# **Nivel 3**
![Error](resources/GridAttack_3.png)

---
# **Nivel 4**
![Error](resources/GridAttack_4.png)

---
# **Nivel 5**
![Error](resources/GridAttack_5.png)

---
# **Nivel 6**
![Error](resources/GridAttack_6.png)

---
# **Nivel 7**
![Error](resources/GridAttack_7.png)

---
# **Nivel 8**
![Error](resources/GridAttack_8.png)

---
# **Nivel 9**
![Error](resources/GridAttack_9.png)

---
# **Nivel 10**
![Error](resources/GridAttack_10.png)

---
# **Nivel 11**
![Error](resources/GridAttack_11.png)

---
# **Nivel 12**
![Error](resources/GridAttack_12.png)

---
# **Nivel 13**
![Error](resources/GridAttack_13.png)

---
# **Nivel 14**
![Error](resources/GridAttack_14.png)

---
# **Nivel 15**
![Error](resources/GridAttack_15.png)

---
# **Nivel 16**
![Error](resources/GridAttack_16.png)

---
# **Nivel 17**
![Error](resources/GridAttack_17.png)

---
# **Nivel 18**
![Error](resources/GridAttack_18.png)

---
# **Nivel 19**
![Error](resources/GridAttack_19.png)

---
# **Nivel 20**
![Error](resources/GridAttack_20.png)

---
# **Nivel 21**
![Error](resources/GridAttack_21.png)

---
# **Nivel 22**
![Error](resources/GridAttack_22.png)

---
# **Nivel 23**
![Error](resources/GridAttack_23.png)

---
# **Nivel 24**
![Error](resources/GridAttack_24.png)

---
# **Nivel 25**
![Error](resources/GridAttack_25.png)

---
# **Nivel 26**
![Error](resources/GridAttack_26.png)

---
# **Nivel 27**
![Error](resources/GridAttack_27.png)

#field {
  display: grid;
  /* type here */
  grid-template-columns: 1fr 1fr 1fr 1fr;
  grid-template-rows: 1fr 1fr 1fr 1fr;
  gap: 15px;
}

#redLand {
  /* type here */
  grid-column-start: 2;
  grid-column-end: 4;
  grid-row-start: 3;
  grid-row-end: 5;
}

---
# **Nivel 28**
![Error](resources/GridAttack_28.png)

---
# **Nivel 29**
![Error](resources/GridAttack_29.png)

---
# **Nivel 30**
![Error](resources/GridAttack_30.png)

---
# **Nivel 31**
![Error](resources/GridAttack_31.png)

#field {
  display: grid;
  /* type here */
  grid-template-rows: 1fr 1fr 1fr 1fr;
  grid-template-columns: 1fr 2fr 1fr;
  gap: 15px;
  grid-template-areas: "r r g" "r r g" "r r g"
  "n n g";
}

#greenLand {
  /* type here */
  grid-area: g;
}

#redLand {
  /* type here */
  grid-area: r;
}

---
# **Nivel 32**
![Error](resources/GridAttack_32.png)

#field {
  display: grid;
  /* type here */
  grid-template-rows: 1fr 1fr 1fr;
  grid-template-columns: 1fr 1fr 1fr;
  grid-template-areas: "g g n" "g g n" "r r r";
  gap: 15px 10px;
}

#greenLand {
  /* type here */
  grid-area: g;
}

#redLand {
  /* type here */
  grid-area: r;
}

---
# **Nivel 33**
![Error](resources/GridAttack_33.png)

---
# **Nivel 34**
![Error](resources/GridAttack_34.png)

---
# **Nivel 35**
![Error](resources/GridAttack_35.png)

---
# **Nivel 36**
![Error](resources/GridAttack_36.png)

---
# **Nivel 37**
![Error](resources/GridAttack_37.png)

---
# **Nivel 38**
![Error](resources/GridAttack_38.png)

#field {
  display: grid;
  /* type here */
  grid-template-rows: 1fr 1fr;
  grid-template-columns: minmax(min-content, 200px) 150px
}

---
# **Nivel 39**
![Error](resources/GridAttack_39.png)

#field {
  display: grid;
  /* type here */
  grid-template-rows: 1fr 1fr;
  grid-template-columns: minmax(max-content, 200px) minmax(min-content, auto)
}

---
# **Nivel 40**
![Error](resources/GridAttack_40.png)

---
# **Nivel 41**
![Error](resources/GridAttack_41.png)

#field {
  display: grid;
  /* type here */
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 15px;
}

---
# **Nivel 42**
![Error](resources/GridAttack_42.png)

#field {
  display: grid;
  /* type here */
  grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
  column-gap: 15px;
}

---
# **Nivel 43**
![Error](resources/GridAttack_43.png)

---
# **Nivel 44**
![Error](resources/GridAttack_44.png)

#field {
  display: grid;
  /* type here */
  gap: 15px;
  grid-template-areas: "r r r" "n g g" "n g g";
}

#greenLand {
  /* type here */
  grid-area: g;
}

#redLand {
  /* type here */
  grid-area: r;
}

---
# **Nivel 45**
![Error](resources/GridAttack_45.png)

#field {
  display: grid;
  /* type here */
  gap: 15px;
  grid-template-rows: 100px 200px 1fr;
  grid-template-columns: repeat(3, 1fr);
  grid-template-areas: "r r n" "b g g" "b g g";
}

#greenLand {
  /* type here */
  grid-area: g;
}

#redLand {
  /* type here */
  grid-area: r;
}

#blueLand {
  /* type here */
  grid-area: b;
}

---
# **Nivel 46**
![Error](resources/GridAttack_46.png)

---
# **Nivel 47**
![Error](resources/GridAttack_47.png)

---
# **Nivel 48**
![Error](resources/GridAttack_48.png)

#field {
  display: grid;
  /* type here */
  grid-template-rows: repeat(4, 1fr);
  grid-template-columns: repeat(4, 1fr);
  grid-auto-flow: column;
  gap: 15px;
}
  
#greenLand {
  grid-column-end: span 3; 
}

---
# **Nivel 49**
![Error](resources/GridAttack_49.png)

---
# **Nivel 50**
![Error](resources/GridAttack_50.png)

---
# **Nivel 51**
![Error](resources/GridAttack_51.png)

---
# **Nivel 52**
![Error](resources/GridAttack_52.png)

---
# **Nivel 53**
![Error](resources/GridAttack_53.png)

---
# **Nivel 54**
![Error](resources/GridAttack_54.png)

---
# **Nivel 55**
![Error](resources/GridAttack_55.png)

---
# **Nivel 56**
![Error](resources/GridAttack_56.png)

---
# **Nivel 57**
![Error](resources/GridAttack_57.png)

---
# **Nivel 58**
![Error](resources/GridAttack_58.png)

---
# **Nivel 59**
![Error](resources/GridAttack_59.png)

#field {
  display: grid;
  /* type-here */
  grid-template-rows: 1fr 1fr;
  grid-template-columns: 2fr 1fr 1fr;
  justify-items: center;
  align-items: center;
}

#field > div {
  height: 50%;
  width: 50%;
  
}

#greenLand {
  /* type-here */
  grid-column: span 2;
}

---
# **Nivel 60**
![Error](resources/GridAttack_60.png)

---
# **Nivel 61**
![Error](resources/GridAttack_61.png)

---
# **Nivel 62**
![Error](resources/GridAttack_62.png)

---
# **Nivel 63**
![Error](resources/GridAttack_63.png)


#field {
  display: grid;
  /* type here */
  grid-template-rows: 1fr 1fr;
  grid-template-columns: 200px 1fr;
  gap: 15px;
}

.redLand {
  /* type here */
  width: 50%;
  height: 50%;
  justify-self: end;
}

---
# **Nivel 64**
![Error](resources/GridAttack_64.png)

#field {
  display: grid;
  /* type here */
  grid-template-rows: 1fr 2fr;
  grid-template-columns: 1fr 2fr;
  gap: 15px;
}

.redLand {
  /* type here */
  height: 50%;
  align-self: center;
}

---
# **Nivel 65**
![Error](resources/GridAttack_65.png)

#field {
  display: grid;
  /* type here */
  grid-template-rows: repeat(3, 1fr);
  grid-template-columns: repeat(3, 1fr);
  
}

.redLand {
  /* type here */
  height: 50%;
  align-self: end;
}

---
# **Nivel 66**
![Error](resources/GridAttack_66.png)

#field {
  display: grid;
  gap: 15px;
  grid-template: 1fr 1fr / 2fr 1fr;
  /* type here */
  justify-items: center;
  align-items: center;
}

#field > div {
  height: 50%;
  width: 50%;
  
}

#redLand {
  /* type here */
  justify-self: end;
  align-self: end;
}

#greenLand {
  /* type here */
  justify-self: start;
  align-self: end;
}

---
# **Nivel 67**
![Error](resources/GridAttack_67.png)

#field {
  display: grid;
  /* type here */
  grid-template-rows: 1fr 1fr 1fr;
  grid-template-columns: 2fr 1fr;
}

#field > div {
  height: 50%;
  width: 50%;
  
}

#redLand {
  /* type here */
  
}

#greenLand {
  /* type here */
  place-self: start end;
}

---
# **Nivel 68**
![Error](resources/GridAttack_68.png)

---
# **Nivel 69**
![Error](resources/GridAttack_69.png)

---
# **Nivel 70**
![Error](resources/GridAttack_70.png)

---
# **Nivel 71**
![Error](resources/GridAttack_71.png)

---
# **Nivel 72**
![Error](resources/GridAttack_72.png)

---
# **Nivel 73**
![Error](resources/GridAttack_73.png)

---
# **Nivel 74**
![Error](resources/GridAttack_74.png)

#field {
  display: grid;
  /* type here */
  grid-template-rows: repeat(4, 1fr);
  grid-template-columns: repeat(4, 1fr);
  gap: 15px;
}

#greenLand {
  /* type here */
  grid-row: 2 / 5;
  grid-column: 2 / 4;
}

---
# **Nivel 75**
![Error](resources/GridAttack_75.png)

#field {
  display: grid;
  /* type here */
  grid-template-rows: repeat(3, 1fr);
  grid-template-columns: repeat(3, 1fr);
  grid-template-areas: "g g b" "g g b" "r r r";
  gap: 15px 10px;
}

#greenLand {
  /* type here */
  grid-area: g;
}

#redLand {
  /* type here */
  grid-area: r;
}

#blueLand {
  /* type here */
  grid-area: b;
}

---
# **Nivel 76**
![Error](resources/GridAttack_76.png)

---
# **Nivel 77**
![Error](resources/GridAttack_77.png)

#field {
  display: grid;
  grid-template-columns: repeat(auto-fill, 1fr);
  /* type here */
  gap: 15px;
  grid-auto-rows: 100px;
  align-content: space-between;
}

#field div:nth-child(3n) {
  /* type here */
  grid-row: span 1;
  grid-column: span 3;
}

---
# **Nivel 78**
![Error](resources/GridAttack_78.png)

#field {
  /* type here */
  grid-template-rows: 1fr 1fr;
  grid-template-columns: 100px 1fr 1fr;
  gap: 15px;
  grid-auto-flow: column;
}

#greenLand {
  /* type here */
  grid-row: span 2;
}

#redLand {
  /* type here */
  grid-row: 2;
}

#blueLand {
  /* type here */
  height: 50%;
  align-self: center;
}

---
# **Nivel 79**
![Error](resources/GridAttack_79.png)

#field {
  /* type here */
  grid-template-rows: repeat(4, 1fr);
  grid-template-columns: repeat(4, 1fr);
  gap: 15px;
}

#greenLand {
  /* type here */
  grid-row-start: 3;
  grid-row-end: 5;
  grid-column-start: 2;
  grid-column-end: 5;
}

#redLand {
  /* type here */
  grid-row-start: 1;
  grid-row-end: 4;
  grid-column-start: 3;
  grid-column-end: 5;
}

---
# **Nivel 80**
![Error](resources/GridAttack_80.png)

#field {
  /* type here */
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}

#greenLand {
  /* type here */
  grid-row: 1 / 2;
  grid-column: 1 / 3;
}

#redLand {
  /* type here */
  grid-row: 1 / 3;
  grid-column: 2 / 4;
}

#blueLand {
  /* type here */
  grid-row: 1 / 5;
  grid-column: 2;
}