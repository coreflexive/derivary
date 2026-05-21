#law

>[!iparam]
>1. $A \in \textsf{Set}$
>2. $R \in A \sim A$
>3. $p \in \mathbb{B} \sim A$

>[!assume]
>3. [[Predicate]] $p$
>4. [[Preorder]] $R$

>[!observe]
>1. $(\forall x, y \mid \mathop{p} x \wedge \mathop{p} y : x \simeq y \equiv (\forall z \mid \mathop{p} z : z \mathbin{R} x \equiv z \mathbin{R} y))$
>2. $(\forall x, y \mid : x \simeq y \equiv (\forall z \mid : z \mathbin{R} x \equiv z \mathbin{R} y))$

>[!observe]
>3. $(\forall x, y \mid \mathop{p} x \wedge \mathop{p} y : x \simeq y \equiv (\forall z \mid \mathop{p} z : y \mathbin{R} z \equiv x \mathbin{R} z))$
>4. $(\forall x, y \mid : x \simeq y \equiv (\forall z \mid : y \mathbin{R} z \equiv x \mathbin{R} z))$
