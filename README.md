# FULL_SUBTRACTOR
# Truth Table and Circuit Diagram
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/351addef-f7bb-4862-9817-616a41b4c882)
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/906152b8-63bc-4f70-9132-6b6b4420b22d)
![image](https://github.com/RESMIRNAIR/FULL_SUBTRACTOR/assets/154305926/7d480140-153a-4a7e-a6d2-5323c6bd4974)
# Program
```
module full_subtractor(a,b,c,diff,borr);
input a,b,c;
output diff,borr;
wire w1,w2,w3,w4;
xor s1(w1,a,b);
not s3(w2,w1);
not s4(w4,c);
and s5(y,w4,b);
xor s2(diff,a,w1);
and s6(w3,w2,a);
or (borr,y,w3);
endmodule
```

# Output
![316436114-8e54267e-87b8-4097-80df-1d98959ffeaa](https://github.com/Vijayananthperumal22/FULL_SUBTRACTOR/assets/107705127/41c8f1b4-a7d3-4bed-81b2-a634c0c41503)

