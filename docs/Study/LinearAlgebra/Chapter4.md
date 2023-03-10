# Chapter. 4 ð³ ç©éµçç¹å¾å¼åç¹å¾åé

> ç©éµçç¹å¾å¼åç¹å¾åéå¯ä»¥ç¨æ¥è®¡ç®å¨$P^{-1}AP$æä¹ä¸çæç®ç©éµï¼è$A$ä¸$P^{-1}AP$è¡¨ç¤ºå¨ä¸ååæ ç³»ä¸çåä¸ä¸ªçº¿æ§åæ¢ã

## 4.1 ç¸ä¼¼ç©éµ
- Def. 4.1.1 **ç¸ä¼¼ç©éµ**ï¼å¯¹äºåé¶æ¹éµ$A$å$B$ï¼å¦æå­å¨å¯éç©éµ$P$ï¼ä½¿å¾ $B= P^{-1}AP$ï¼å°±ç§°$A$ç¸ä¼¼äº$B$ï¼è®°ä½ $A \sim B$ãç§° $B$ä¸º$A$çç¸ä¼¼ç©éµï¼ç§°$P$ä¸º$A$å°$B$çç¸ä¼¼åæ¢ç©éµã
- ä¸ä¸ªæ§è´¨ï¼
    - èªåæ§ï¼å¯¹ä»»æç©éµï¼é½æç«$A \sim A$ï¼
    - å¯¹ç§°æ§ï¼è¥ $A \sim B$ï¼é£ä¹ $B \sim A$ ;
    - ä¼ éæ§ï¼å¦æ$A \sim Bï¼ B \sim C$ï¼é£ä¹ $A \sim C$;
- å¶ä»æ§è´¨ï¼
    - å¦æ $A \sim B$ ï¼é£ä¹$|A| = |B|$ï¼ä»è$A$å$B$çå¯éæ§ç¸åï¼
    - è¥ $A \sim B$ï¼ä¸ $A$ æè $B$å¯éï¼å $A^{-1} \sim B^{-1}$
    - è¥ $A \sim B$ï¼é£ä¹ $A^{n} \sim B^{n}ï¼kA \sim kB$ï¼å¶ä¸­$n$ä¸ºèªç¶æ°ï¼$k$ä¸ºä»»æå®æ°ï¼
    - è¥ $A \sim B$ï¼å $f(A) \sim f(B)$ï¼å¶ä¸­$f(x) = a_n x^{n} +,..., + a_1 x + a_0$ ä¸ºä»»æå¤é¡¹å¼ã

## 4.2 ç¹å¾å¼åç¹å¾åé

- å¯¹äºä¸ä¸ª $n$ é¶æ¹éµAï¼å¦ææ $P = (\xi_1, \xi_2, ..., \xi_m), \Lambda = diag(\lambda_1,...,\lambda_n)$ï¼ä½¿å¾$A = P \Lambda P^{-1}$ï¼å$AP = P\Lambda$ï¼æä»¥æ $A\xi_i = \lambda_i \xi_i, i = 1,2,...,n$ 

- Def. 4.2.1 ==(ç¹å¾å¼ãç¹å¾åé)== è®¾$A$æ¯å®æ°å$R$æèå¤æ°å$C$ä¸çä¸ä¸ªæ¹éµï¼ $\lambda \in C$ï¼è¥å­å¨éé¶åé $\xi$ ä½¿å¾ $A \xi =\lambda \xi$ï¼åç§° $\lambda$ ä¸ºç©éµ$A$ç**ç¹å¾å¼**ï¼$\xi$ ç§°ä¸º$A$çå±äºç¹å¾å¼$\lambda$ ç**ç¹å¾åé**ã

- ç¹å¾å¼çéæ ¹ï¼
  
- å®ç 4.2.1 è®¾æ¹ç¨Aæç¹å¾å¼ $\lambda, \xi_1, \xi_2$ä¸ºå±äº $\lambda$ çç¹å¾åéï¼åä»ä»¬çä»»æä¸ç­äºé¶åéççº¿æ§ç»å $\eta = k_1 \xi_1 + k_2 \xi_2 (k_1, k_2 \in R)$ä»æ¯å±äº $\lambda$ çç¹å¾åéã
- å¦ä½æ±åºAçå¨é¨ç¹å¾å¼åå¨é¨ç¹å¾åéï¼å ä¸ºæ¹ç¨ $A \xi = \lambda \xi$ç­ä»·äºé½æ¬¡çº¿æ§æ¹ç¨ç»$(\lambda E - A)\xi = \theta$ï¼ææ±ç¹å¾å¼ãç¹å¾åéä¹å°±æ¯æ± $(\lambda E - A)x = \theta$ éé¶è§£çé®é¢ãç±äºé½æ¬¡çº¿æ§æ¹ç¨ç»æéé¶è§£çåè¦æ¡ä»¶æ¯**ç³»æ°è¡åå¼ä¸º0**ï¼ä¹å°±æ¯ $|\lambda E - A| = 0$ï¼ç±æ­¤å¯ä»¥æ±å¾ç¹å¾å¼ $\lambda$ï¼è¿ä¸æ­¥å¯ä»¥æ±å¾$(\lambda E - A)x = \theta$ ç**éé¶è§£**ï¼è¿å°±æ¯å±äºç¹å¾å¼çç¹å¾åéã

- Def. 4.2.2 **ç¹å¾å¤é¡¹å¼/ç¹å¾æ¹ç¨/ç¹å¾ç©éµ** ï¼$|\lambda E - A|$ç§°ä¸º$A$çç¹å¾å¤é¡¹å¼ï¼æ¹ç¨$|\lambda E - A| = 0$ç§°ä¸º$A$çç¹å¾æ¹ç¨ï¼æ¹ç¨ $|\lambda E - A| = 0$çè§£å°±ç§°ä¸º$A$çç¹å¾æ ¹ï¼è $\lambda E - A$ç§°ä¸º$A$çç¹å¾ç©éµã
  
ãè®¡ç®æ­¥éª¤ï¼ç¥ã

- å®ç 4.2.2 è¥$f(x)$ä¸º$x$çå¤é¡¹å¼ï¼ç©éµ$A$æç¹å¾å¼$\lambda$ï¼å$f(A)$ æç¹å¾å¼$f(\lambda)$ï¼
    - ä¹å°±æ¯è¯´ç¹å¾å¼çè¿ç®å³ç³»å¯¹åºçç©éµçè¿ç®å³ç³»ï¼$(B = 5A)$
- å®ç 4.2.3 ç¸ä¼¼ç©éµå·æç¸åçç¹å¾å¤é¡¹å¼ï¼ä»èå®ä»¬å·æç¸åçç¹å¾å¼ï¼å¶è¡åå¼çå¼ä¹æ¯ç¸åçã
- Def. 4.2.3 è¿¹ å®ä¹ $tr(A) = \sum \limits^{n}_{i = 1}{a_ii}$ ä¸ºç©éµ $A = (a_{ij})_{n \times n}$çè¿¹ã
- å®ç 4.2.4 è¥ $n$ é¶ç©éµ$A$çç¹å¾å¼ $\lambda_1, ... , \lambda_n$ï¼åæ $tr(A) = \sum \limits^{n}_{i=1}{\lambda_i}$, $|A| = \prod \limits^{n}_{i = 1}{\lambda_i}$
- æ¨è®º 4.2.5 ç¸ä¼¼ç©éµæç¸åçè¿¹åç¸åçè¡åå¼
- å®ç 4.2.6 è®¾$A$æ¯ä¸ä¸ªåå¯¹è§ç©éµãç©éµãï¼åAçç¹å¾å¤é¡¹å¼æ¯ $A_1, A_2, ... , A_m$çç¹å¾å¤é¡¹å¼çä¹ç§¯ï¼äºæ¯$A_1, A_2, ..., A_m$çææç¹å¾å¼å°±æ¯Açææç¹å¾å¼ã

## 4.3 ç©éµå¯å¯¹è§åçæ¡ä»¶

- å®ä¹ 4.3.1 å¯å¯¹è§åï¼è¥æ¹éµ$A$  **ç¸ä¼¼äºä¸ä¸ªå¯¹è§ç©éµ**ï¼åç§°$A$å¯å¯¹è§åã
- å®ç 4.3.1 $n$ é¶ç©éµå¯å¯¹è§åçåè¦æ¡ä»¶æ¯æ$n$**ä¸ªçº¿æ§æ å³çç¹å¾åé**ï¼
    - <u>å¯¹è§ç©éµçä¸»å¯¹è§çº¿ç±ç¹å¾å¼ææï¼ç¸ä¼¼åæ¢ç©éµç±å±äºç¸åºç¹å¾å¼çç¹å¾åéææ</u>ã
- å®ç 4.3.2 å±äºä¸åç¹å¾å¼çç¹å¾åéçº¿æ§æ å³
- æ¨è®º 4.3.3 è¥$n$é¶ç©éµæ$n$ä¸ª**äºä¸ç¸åçç¹å¾å¼**ï¼é£ä¹ç©éµå¯å¯¹è§å
- å®ç 4.3.4 è¥ $\lambda_1, \lambda_2, ..., \lambda_m$ æ¯ç©éµ$A$çä¸åç¹å¾å¼ï¼è$A$çå±äº $\lambda_i$ççº¿æ§æ å³çç¹å¾åéä¸º $\alpha_{i1},\alpha_{i2},...,\alpha_{is_i}, ( i = 1,2,...,m)$ï¼ååéç» $\alpha_{11}, ...,\alpha_{1s_1}, \alpha_{21},...,\alpha_{2s_2},...,\alpha_{m1},...,\alpha_{ms_m}$çº¿æ§æ å³ã
- å®ç 4.3.5 è®¾ $\lambda_0$ æ¯$n$é¶æ¹éµ$A$ç$k$éç¹å¾å¼ï¼åAçå±äºç¹å¾å¼$\lambda_0$ççº¿æ§æ å³çç¹å¾åéä¸ªæ°ä¸è¶è¿$k$ã
- ððå®ç 4.3.6 $n$é¶æ¹éµ$A$å¯å¯¹è§åçåè¦æ¡ä»¶æ¯æ¯ä¸ª $k_i$éç¹å¾å¼ $\lambda_i$ å¯¹åºçç¹å¾ç©éµ $\lambda_i E- A$çç§©ä¸º $n - k_i$
-  $A$æéç¹å¾å¼çæ¶å$A$æ¯å¦å¯å¯¹è§åçå¤å®æ¹æ³

- å¯¹æ¯ä¸ªéç¹å¾å¼ $\lambda_i$ï¼ æ±ç©éµ $\lambda_i E- A$çç§© $r_i$ï¼ å¦æå¯¹æ¯ä¸ªéç¹å¾å¼ $\lambda_i ï¼ n - r_i$ é½ç­äº $\lambda_i$çéæ°ï¼é£ä¹Aå¯ä»¥å¯¹è§åï¼å¦åä¸å¯ï¼

- ç©éµç¸ä¼¼å¯¹è§åçæ¹æ³ï¼

    1. è§£ç¹å¾æ¹ç¨ï¼å¾å°ç¹å¾å¼ï¼å¯ä»¥æå¤éçç¹å¾å¼åºæ¥ï¼
    2. å¯¹æ¯ä¸ªç¹å¾å¼ï¼è§£é½æ¬¡æ¹ç¨ç» $(\lambda_i E - A)x = \theta$ï¼å¾å°ä¸ä¸ªåºç¡è§£ç³»ï¼$\alpha_{i1},... \alpha_{ir_i}$ãå¦æå­å¨æä¸ª $i$ ä½¿å¾ $r_i < s_i$ï¼é£ä¹ä¸å¯å¯¹è§åï¼
    3. å¦æææç$r_i = s_i$ï¼é£ä¹ä»¤ $P = (\alpha_{11}, ... ,\alpha_{1s_1},...)$ï¼å³å¯å¾ $P^{-1}AP  = \Lambda = diag (\lambda_1, ..,\lambda_1, \lambda_2,...\lambda_2, ..., \lambda_m, ..., \lambda_m)$ï¼
    4. ç±äºé½æ¬¡çº¿æ§æ¹ç¨ç»çåºç¡è§£ç³»ä¸æ¯å¯ä¸çï¼æä»¥$P$çåå¼ä¹ä¸æ¯å¯ä¸çï¼ä½æ¯ç±äº$P^{-1}AP$ çä¸»å¯¹è§çº¿çåç´ æ¯$A$çå¨ä½ç¹å¾å¼ï¼æä»¥é¤äºæ¬¡åºä¸åå¤ï¼$P^{-1}AP$æ¯å¯ä¸ç¡®å®çã

## 4.4 æ­£äº¤ç©éµåæ½å¯ç¹æ­£äº¤åæ¹æ³

- åéåç§¯ï¼å¯¹åºä½ç½®ä¹èµ·æ¥ç¶åç¸å ï¼
    - $(\alpha, \beta) = (\beta, \alpha)$
    - $(k\alpha, \beta) = k(\alpha,  \beta)$
    - $(\alpha + \gamma , \beta) = (\alpha, \beta) + (\gamma, \beta)$
    - $(\alpha, \alpha) \geq 0; (\alpha, \alpha) = 0$ï¼å½ä¸ä»å½ $\alpha = \theta$

- åéå¤¹è§ï¼ $\arccos(\dfrac{(\alpha, \beta)}{\Vert \alpha \Vert \Vert \beta \Vert})$

- **åéæ­£äº¤**ï¼ $(\alpha, \beta) = 0$ï¼é£ä¹ $\alpha, \beta$ å°±æ¯æ­£äº¤çã
- æ­£äº¤åéç»ï¼å¦æä¸ä¸ª==ä¸å«é¶åéçåéç»ä¸­åéä¸¤ä¸¤æ­£äº¤==ï¼é£ä¹å°±ç§°è¿ä¸ªåéç»ä¸ºæ­£äº¤åéç»ï¼å¦æä¸ä¸ªæ­£äº¤åéç»ä¸­çåéé½æ¯åä½åéï¼é£ä¹è¯¥åéç»ç§°ä¸ºæ åæ­£äº¤åéç»ï¼æ³åéç»ï¼ï¼

- **Schmidtæ­£äº¤åï¼çº¿æ§æ å³ç»æ­£äº¤è§èåçæ¹æ³ï¼**ï¼ç±çº¿æ§æ å³åéç» $\alpha_1, \alpha_2,...,\alpha_n$ å¯ä»¥æé åºä¸ä¹ç­ä»·çæ­£äº¤åéç» $\xi_1, \xi_2,...,\xi_n$ ï¼å¹¶ä¸ $\xi_i$ å¯ä»¥è¡¨ç¤ºä¸º $\alpha_1,...,\alpha_i$ççº¿æ§ç»åï¼
    > å¨ç©éµæä½ä¸­ï¼ç»å¸¸éè¦ä»ä¸ç»çº¿æ§æ å³çåéæé åºä¸ç»åç­ä¸ªæ°ç­ä»·çä¸¤ä¸¤æ­£äº¤çåéï¼å¹¶ä¸éè¦ä½¿æ¯ä¸ªåéçæ¨¡ç­äº1ï¼ä¹å°±æ¯æ¯ä¸ªæ°åéé½æ¯åä½åéï¼è¿ç§åæ³å«åçº¿æ§æ å³åéç»çæ­£äº¤è§èåãæ½å¯ç¹ï¼Schmidtï¼æ­£äº¤åæ¹æ³å°±æ¯æ¯è¾å¸¸ç¨çæ­£äº¤è§èåæ¹æ³ã

- $y_1 = x_1$ æ¯ç¬¬ä¸ä¸ªåéï¼åé¢ææçåéé½è¦åå®æ­£äº¤$(y_1, y_i) = 0$ï¼
- $y_2 = x_2 + k_{21} y_1$ï¼æ ¹æ®æ­£äº¤æ¡ä»¶å¯å¾ $k_{21} = - \dfrac{(x_2, y_1)}{(y_1,y_1)}$
- $y_3 = x_3 + k_{31}y_1 + k_{32}y_2$ï¼åçè®¡ç®åº $k_{32} = - \dfrac{(x_3, y_2)}{(y_2, y_2)}, k_{31} = - \dfrac{(x_3, y_1)}{(y_1, y_1)}$
- ....ç»§ç»­æ¨çï¼å¾ç»è®ºï¼
- $y_n = x_n + k_{n1} x_1 + k_{n2} x_2 + ... + k_{n,n-1} x_{n-1}$ï¼ä¸ $k_{nk} = - \dfrac{(x_{n}, y_k)}{(y_k, y_k)}$
- æå$z_i = \dfrac{y_i}{| y_i |}$ï¼è¿è¡åä½åå³å¯ï¼

- æ­£äº¤ç©éµï¼å¦æå®æ¹éµ$A$æ»¡è¶³$A^T A = E$ ,é£ä¹ç§°Aä¸ºæ­£äº¤ç©éµï¼
    - æ§è´¨ãå¾è¡¥åã
## 4.5 å®å¯¹ç§°ç©éµçå¯¹è§å

- å¦æä¸ä¸ªå®ç©éµï¼ç©éµä¸­ææçåç´ é½æ¯å®æ°ï¼ï¼$A$å·æå¯¹ç§°æ§ï¼ä¹å°±æ¯$A^T = A$ï¼å°±ç§°å®ä¸ºå®å¯¹ç§°ç©éµï¼
    - å®å¯¹ç§°ç©éµä¸å®å¯å¯¹è§åï¼
    - ç¹å¾å¼ä¸å®æ¯å®æ°ï¼
- å¦æ$A$æ¯å®å¯¹ç§°ç©éµï¼é£ä¹å­å¨åé¶çæ­£äº¤ç©éµ$P$ä½¿å¾$P^TAP$æ¯å®å¯¹è§ç©éµï¼ä»èå®å¯¹ç§°ç©éµå¯å¯¹è§åï¼

## 4.6 Jordanæ åååå¥å¼å¼åè§£

- ä»»æ $m \times n$é¶å®ç©éµåå¯åè§£æ $U\Sigma V^T$çå½¢å¼ï¼å¶ä¸­$Uï¼V$æ¯$m$é¶å$n$é¶æ­£äº¤ç©éµï¼$\Sigma = diag(\sigma_1, \sigma_r,0,..,0)_{ m \times n}$ï¼$r$ä¸ºç©éµçç§©ï¼ä¸å¯ä»¥ä¿è¯ $\sigma_1 \geq \sigma_2 \geq \sigma_3 ... \geq \sigma_r > 0$ï¼è¿äº $\sigma$ å°±æ¯å¥å¼å¼ã


> éç»´ç®æ³ä¸­çç¹å¾åè§£ï¼æ¯å¦åfeature reductionçPCAï¼åæ°æ®åç¼©ï¼ä»¥å¾ååç¼©ä¸ºä»£è¡¨ï¼çç®æ³è¿å¯ä»¥ç¨äºæ¨èç³»ç»ãä»¥åèªç¶è¯­è¨å¤çç­é¢åï¼å¦åæç´¢å¼æè¯­ä¹å±æ¬¡æ£ç´¢çLSIï¼Latent Semantic Indexingï¼ã