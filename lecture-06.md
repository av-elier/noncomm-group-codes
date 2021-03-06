## Прямая сумма модулей

\Df Модуль $M$ является прямой суммой своих подмодулей $M_1, \ldots, M_k$,
если (1) он является их суммой и (2) равенство
$$
    m_1 \oplus \ldots \oplus m_k = 0
$$
возможно тогда и только тогда, когда все $m_i = 0$.

\Exec Доказать, что условие (2) в определении выше равносильно любому из
следующих:

1. Для любого $i$: $M_i \cap (M_1 + \ldots + M_k) = 0$ (сумма без $M_i$).

2. Любой элемент $m \in M$ представим единственным образом в виде
   $m = m_1 + \ldots + m_k$.

3. Для всех…

\Nt Мы определили прямую сумму подмодулей одного модуля, то есть
разложение модуля в прямую сумму своих подмодулей.

Рассмотрим $k$ различных $R$-модулей: $M_1, \ldots, M_k$. Рассмотрим
следующий объект, называемый внешней прямой суммой:
$$
    %M^* = 
    M_1 \oplus \ldots \oplus M_k =
        \{ \bbar{m}=(m_1, \ldots , m_k) \mid
            m_i \in M_i \}.
$$

\Stm Если $M_i$ это подмодули некоторого модуля $M$, то
$$ 
    M_1 + \ldots + M_k = M_1 \oplus \ldots \oplus M_k.
$$
В частности, $\{(0, \ldots, 0, m_i, 0 , \ldots, 0)\} \simeq M_i$.

\Df Пусть $\{m_\alpha \}_{\alpha \in A} \subset M$. Такой набор
называется свободным, если из выполнения равенства $\sum r_i m_i = 0$
следует $r_i = 0$ для всех $i$.

\Nt Свободный набор не может содержать нуля.

\Df Набор $\{m_\alpha \}_{\alpha \in A} \subset M$ называется системой
образующих элементов модуля $M$, если
$$
    M = \left\{ \sum r_i m_i \right\}.
$$

В классе всех модулей выделим класс конечнопорождённых модулей.

\Ex Пусть $A$ это абелева группа $\Z_2 \oplus \Z_5$. Она является
модулем над \Z. Её система образующих: $\{ (1, 0), (0,1) \}$. Она,
однако, не является свободной. Другая система: $\{ (1, 1) \}$. Снова
не является свободной.

\Exec Можно ли группу и примеры выше рассмотреть как $B$-модуль, где
$B$ это $\Z_n$, так, чтобы нашлась свободная порождающая система.

\Df  Модуль $M$ называется циклическим, если $M = R\{m_0\}$.

\Df Рассмотрим $R$-свободное множество образующих элементов. Это
множество называется $R$-базисом модуля $M$.

\Stm Рассмотрим в модуле $M$ $R$-базис $\{ m_\alpha \}$. Тогда
любой элемент $m\in M$ единственным образом представим в виде. Обратное
также справедливо.

\Df $R$-модуль $M$ называется свободным, если в нём есть $R$-базис.

\Nt Не все модули обладают базисом.

\Df $R$-модуль называется модулем без кручения, если выполняется
импликация
$$
    rm = 0 \Rightarrow r = 0 \wedge m = 0.
$$

\ex Пусть $\F_q^m$ это $\F_q$-модуль без кручения.

В модулях вводятся понятия гомоморфизмов, подмодулей, фактормодулей,
которые обладают естественными свойствами, перенесёнными из теории
групп.
