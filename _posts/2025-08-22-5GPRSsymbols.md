---
title: "5GPRSsymbols"
header:
  overlay_color: "#333"
categories: 
  - 5G
toc: true


---

**此处假设基站只传输PRS，不传输数据**

## PRS symbols映射



![](C:\Users\Mr.zhou\AppData\Roaming\Typora\typora-user-images\image-20250822120552659.png)



---

1s内，总的PRS symbols为$1000\left(\left(\frac{N_{\rm{SC}}^{\rm{RB}}}{K_{\rm{comb}}^{\rm{PRS}}}L_{\rm{PRS}}\right)N_{\rm{RB}}^{\mu}\frac{N^{\rm{subframe},\mu}_{\rm{symbol}}}{N^{\rm{slot}}_{\rm{symbol}}}\right)=1000\left(\left(\frac{N_{\rm{SC}}^{\rm{RB}}}{K_{\rm{comb}}^{\rm{PRS}}}L_{\rm{PRS}}\right)N_{\rm{RB}}^{\mu}N^{\rm{subframe},\mu}_{\rm{slot}}\right)$

带宽为10 MHz情况下，$N_{\rm{RB}}^{\mu} \in \{52,24,11\}$，$\mu \in \{0,1,2\}$

---

## 说明

- **符号数配置[3GPP 38.211]**

<img src="C:\Users\Mr.zhou\AppData\Roaming\Typora\typora-user-images\image-20250822120754673.png" style="zoom: 50%;" />

- **示例中 $K_{\rm{comb}}^{\rm{PRS}} = 4$， $l_{\rm{start}}^{\rm{PRS}} = 1$， $L_{\rm{PRS}} = 12$，表明该slot中，有12个符号，同一时域上有$\frac{N_{\rm{SC}}^{\rm{RB}}}{K_{\rm{comb}}^{\rm{PRS}}}=3$个PRS symbols，符号映射方式参考Table 7.4.1.7.3-1[3GPP 38.211]，从 $l_{\rm{start}}^{\rm{PRS}} = 1$开始符号以{0,2,1,3,0,2,1,3,0,2,1,3,0,2,1,3}**

<img src="C:\Users\Mr.zhou\AppData\Roaming\Typora\typora-user-images\image-20250822120803379.png" style="zoom:50%;" />

- **$N_{\rm{RB}}^{\mu}$取值见表Table 5.3.2-1[3GPP 38.101]**

![](C:\Users\Mr.zhou\AppData\Roaming\Typora\typora-user-images\image-20250822120800396.png)

