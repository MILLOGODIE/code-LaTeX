# code-LaTeX
$\begin{array}{lll}
\mathbb{P}(X_{2k}=0) &=&\displaystyle \sum_{\substack{\epsilon_0,\ldots,\epsilon_{2k-1}\in \{-1,1\}\\ \text{ tels que } \epsilon_0+\cdots+\epsilon_{2k-1}= \,0}} \mathbb{P}(X_1=X_0+\epsilon_0,\ldots,X_{2k}=X_{2k-1}+\epsilon_{2k-1})\\[.85cm]
&=& \displaystyle\sum_{\text{idem}} P(0,\epsilon_0)P(\epsilon_0,\epsilon_0+\epsilon_1)\cdots P(\epsilon_0+\cdots+\epsilon_{2k-2},\epsilon_0+\cdots+\epsilon_{2k-2}+\epsilon_{2k-1})\\[.5cm]
&=&\displaystyle\sum_{\text{idem}} \left(\dfrac{1}{2}\right)^{2k}= N\left(\dfrac{1}{2}\right)^{2k},
\end{array}$
