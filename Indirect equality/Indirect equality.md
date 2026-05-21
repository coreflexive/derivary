#law

>[!iparam]
>1. $A \in \textsf{Set}$
>2. $R \in A \sim A$
>3. $p \in \mathbb{B} \sim A$

>[!assume]
>4. [[Predicate]] $p$
>5. [[Partial order]] $R$

>[!observe]
>6. $(\forall x, y \mid \mathop{p} x \wedge \mathop{p} y : x = y \equiv (\forall z \mid \mathop{p} z : z \mathbin{R} x \equiv z \mathbin{R} y))$
>7. $(\forall x, y \mid : x = y \equiv (\forall z \mid : z \mathbin{R} x \equiv z \mathbin{R} y))$

>[!observe]
>8. $(\forall x, y \mid \mathop{p} x \wedge \mathop{p} y : x = y \equiv (\forall z \mid \mathop{p} z : y \mathbin{R} z \equiv x \mathbin{R} z))$
>9. $(\forall x, y \mid : x = y \equiv (\forall z \mid : y \mathbin{R} z \equiv x \mathbin{R} z))$
