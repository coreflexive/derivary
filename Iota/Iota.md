#combinator

>[!iparam]
>1. $A \in \textsf{Set}$

>[!param]
>2. $p \in \mathbb{B} \sim A$

>[!assume]
>3. [[Predicate]] $p$
>4. [[One|one]] $p$

>[!define] iota-charn
>5. $(\forall y \mid : y = \mathop{\textsf{iota}} p  \; \equiv \; (\forall z \mid : \mathop{p} z \equiv z = y))$

>[!observe] iota-self
>1. $(\forall z \mid : \mathop{p} z \; \equiv \; z = \mathop{\textsf{iota}} p)$ #needs-writeup 

>[!observe] iota-id
>2. $(\forall y \mid : y = \mathop{\textsf{iota}} \; (=y)))$ #needs-writeup 
