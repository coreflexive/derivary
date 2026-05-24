#combinator 

>[!iparam]
>1. $A \in \textsf{Set}$
>2. $B \in \textsf{Set}$

>[!param]
>1. $R \in A \sim B$
>2. $x \in B$

>[!assume]
>1. [[Simple]] $R$
>2. $x \in \mathop{\textsf{dom}}$

>[!define] Apply
>1. **apply** $R$ $x$ $\triangleq$ [[Iota|iota]] $(y \mid : y \mathbin{R} x)$

>[!define] Apply (sugared)
>2. $R.x \triangleq$ **apply** $R$ $x$
