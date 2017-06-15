## DFT计算相关
### 计算表面能公式
晶体的表面能DFT计算核心公式[^5-1]
$$E_{sur}=(E_{tol} - nE_{cell})/S$$
$E_{sur}$代表表面能，$E_{tol}$代表沿着特定方向构建的超胞的总能，$E_{cell}$代表单胞的总能，$S$代表超胞中还要的特定面的面积，$n$代表超胞中所含单胞的个数。
[^5-1]: Y. Wang, J. Chen, P. Wang, L. Chen, Y.-B. Chen, and L.-M. Wu, “Syntheses, Growth Mechanism, and Optical Properties of [001] Growing Bi 2 S 3 Nanorods,” J. Phys. Chem. C, vol. 113, no. 36, pp. 16009–16014, 2009.
### 计算缺陷形成能公式
- 空位形成能的计算公式如下: [^5-2]
$$E_{f}=E(defect,q)-E(pure)+\mu_{S}+q(E_{VBM}+\varepsilon_F)$$
其中,$E(defect,q)$代表超胞中存在一个S空位电荷价态为q的总能，$E(pure)$代表完整超胞中的总能，$\mu_{S}$代表硫的化学化学势，$E_{VBM}$代表价带顶的能量(可以是经过矫正的能量)，$\varepsilon_{F}$代表从费米能级处计算得到的费米能级的测试值。
[^5-2]: D. Guo, C. Hu, and C. Zhang, “First-principles study on doping and temperature dependence of thermoelectric property of Bi2S3 thermoelectric material,” Mater. Res. Bull., vol. 48, no. 5, pp. 1984–1988, 2013.
- 缺陷形成能[^5-3]
$$E_d(D^{(q)},\mu)=E_f(D^{(q)})-\mathop{\Sigma}\limits_{\alpha} n_{\alpha}\Delta \mu_{\alpha}+q_{e}\mu_{e} $$
其中，$$E_{f}(D^{(q)})=E(D^{(q)})-E_{bulk}-\mathop{\Sigma}\limits_{\alpha}n_{\alpha}\Delta \mu_{\alpha}$$
代表对应于标准状态下的缺陷的形成能，$E(D^{(q)})$代表包含缺陷$D$，和额外电荷量$q$的总能，$E_{bulk}$代表完美超晶胞块体材料的总能，$n_{\alpha}$代表缺陷态下转移的原子数量，$E_{\alpha}$代表这些原子标准态下的能量.
[^5-3]: R. Chmielowski, D. Péré, C. Bera, I. Opahle, W. Xie, S. Jacob, F. Capet, P. Roussel, A. Weidenkaff, G. K. H. Madsen, and G. Dennler, “Theoretical and experimental investigations of the thermoelectric properties of Bi2S3,” J. Appl. Phys., vol. 117, no. 12, pp. 0–10, 2015.
